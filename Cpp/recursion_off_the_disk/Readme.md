A self-staging PE binary that achieves hardcoded injection into Teams.exe on Windows 10 using the EarlyBird injection methodology. 

The binary works by passing useful information (stage, threadId) to the next stage before terminating. This breaks the process tree and obfuscates control flow graphs such that it bypasses the most up to date Windows Defender definitions as of 0900 PST 11 December 2022.

![image](https://user-images.githubusercontent.com/22229087/206916933-da7172a2-583d-4f86-b2fe-eb52fea12f75.png)