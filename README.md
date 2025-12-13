# Eggsploit
The original source for Eggsploit, an exploit that operates through a vulnerability (OverrideLockViewGamelayout) in the client to get a Studio UI up until September 2013.
## Building
Run these commands:
```
git clone https://github.com/ZwDaNk/Eggsploit
cd Eggsploit
```
Build for x86-64:
```
msbuild Eggsploit.sln /p:Configuration=Release /p:Platform=x64
```
To build for x86/Win32:
```
msbuild Eggsploit.sln /p:Configuration=Release /p:Platform=Win32
```
