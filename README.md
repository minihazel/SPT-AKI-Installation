# Installing SPT-AKI
This guide will provide you a step-by-step instruction manual on how to properly install SPT-AKI using latest version of Escape From Tarkov.

If you would rather watch a video covering the same procedure as [Section 2](https://github.com/minihazel/SPT-AKI-Installation/blob/main/README.md#section-2), please click this link:

  [SPT 20575 to 20243](https://streamable.com/n7ldlh)


# Prerequisites

Escape From Tarkov: [Buy here](https://www.escapefromtarkov.com/preorder-page)

7-Zip: [Download here](https://www.7-zip.org/download.html)

  (Download  `.exe` `64-bit` `Windows x64`)

  [.NET 4.7.2 Developer Pack Installer](https://dotnet.microsoft.com/en-us/download/dotnet-framework/thank-you/net472-developer-pack-offline-installer)

  [Runtime Desktop 6.0.4 Windows x64 Installer](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-6.0.4-windows-x64-installer)

  [Runtime Desktop 8.0.3 Windows Installer](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-8.0.3-windows-x86-installer)
  


## Notes
As of writing, the date is 2022-12-04 (December 4th 2022) and live Tarkov is on 0.12.12.32.20575.

This guide will show you installation of SPT-AKI `3.3.0` which is the latest stable release.

[Installing SPT-AKI](https://github.com/minihazel/SPT-AKI-Installation/blob/main/README.md#installing-spt-aki) - The start

[Prerequisites](https://github.com/minihazel/SPT-AKI-Installation/blob/main/README.md#prerequisites) - The prerequisites necessary to follow this page

[Notes](https://github.com/minihazel/SPT-AKI-Installation/blob/main/README.md#Notes) - This page

[Section 1](https://github.com/minihazel/SPT-AKI-Installation/blob/main/README.md#section-1) - Copying LIVE Tarkov to a new folder

[Section 2](https://github.com/minihazel/SPT-AKI-Installation/blob/main/README.md#section-2) - Downloading and installing SPT-AKI AND downgrading.

[Section 3](https://github.com/minihazel/SPT-AKI-Installation/blob/main/README.md#section-3) - Downloading and installing SPT-AKI WITHOUT downgrading.

[Common Errors](https://github.com/minihazel/SPT-AKI-Installation/blob/main/README.md#common-errors) - Common errors and how to fix them


## Section 1

Copying live Tarkov to a new folder

- Open your Escape From Tarkov folder. Mine is here: `G:\Battlestate Games\EFT`

- Select ALL files in the folder and COPY them

  ![alt text](https://i.imgur.com/cyBG8tN.png)

- Create a new folder somewhere else (preferably somewhere like C:\)

- Name it `SPT 3.3.0`

  ![alt text](https://i.imgur.com/xZbIYrJ.png)

- PASTE your copied Tarkov files into your `SPT 3.3.0` folder

## Section 2

Downloading and installing SPT-AKI AND downgrading

(If you'd rather not downgrade, head to [Section 3](https://github.com/minihazel/SPT-AKI-Installation/blob/main/README.md#section-3))

- Open this link: https://hub.sp-tarkov.com/files/file/16-spt-aki/

- Click on DOWNLOAD (It's the big blue button on the page)

- Scroll down until you see Downloads

- Click `RELEASE-SPT-3.3.0-20243.zip`

  ![alt text](https://i.imgur.com/KooXbNc.png)

- Open this link: https://hub.sp-tarkov.com/files/file/204-aki-patcher/#versions

- Find the text that says `Version xxx to xxx` (the version on the RIGHT -> -> is the version we're looking for)

- In this case, Version 12.12.32.20575 to 12.12.32.20243

  ![alt text](https://i.imgur.com/C3Vw00b.png)

- Click one of the two yellow download links

- Click `GO TO LINK`

- Download the zip file (Should look something like this: `Patcher_12.12.32.20575_to_12.12.32.20243.zip`)

- Open the `SPT 3.3.0` folder you created in [Section 1](https://github.com/minihazel/SPT-AKI-Installation#section-1).

- Put the Patcher zip file into `SPT 3.3.0` folder.

- Open the Patcher zip file.

- Extract / drag and drop these two into your `SPT 3.3.0` folder -> Aki_Patches and patcher.exe

  ![alt text](https://i.imgur.com/wJ9ewza.png)
  
- Launch / Run `patcher.exe` and let it work.

  ![alt text](https://i.imgur.com/QXDhvOW.png)

- Drag and drop the `RELEASE-SPT-3.3.0-20243.zip` file you downloaded earlier into your `SPT 3.3.0` folder

  ![alt text](https://i.imgur.com/8gvOOT4.png)

- Right click the zip file -> `7-Zip` -> `Extract Here` and let it work

  ![alt text](https://i.imgur.com/VEU7DiP.png)

- Run `Aki.Server.exe`, then run `Aki.Launcher.exe`

- Make your account, log in, then run the game with the launcher


## Section 3

Downloading and installing SPT-AKI WITHOUT downgrading

NOTE: This section can be used for any FUTURE versions unless the process changes.

- Open this link: https://hub.sp-tarkov.com/files/file/16-spt-aki/

- Click on DOWNLOAD (It's the big blue button on the page)

- Scroll down until you see Downloads

- Click `RELEASE-SPT-3.3.0-20243.zip` (we're doing `RELEASE-SPT-3.3.0-20243`)

  ![alt text](https://i.imgur.com/KooXbNc.png)

- Open the `SPT 3.3.0` folder you created in [Section 1](https://github.com/minihazel/SPT-AKI-Installation#section-1).

- Drag and drop the `RELEASE-SPT-3.3.0-20243.zip` file you downloaded earlier into your `SPT 3.3.0` folder

  ![alt text](https://i.imgur.com/8gvOOT4.png)

- Right click the zip file -> `7-Zip` -> `Extract Here` and let it work

  ![alt text](https://i.imgur.com/VEU7DiP.png)

- Run `Aki.Server.exe`, then run `Aki.Launcher.exe`

- Make your account, log in, then run the game with the launcher

## Common Errors
There are some common errors you may run into. Whether you missed a step or have missing internal prerequisites.

### Delta failed to decode ✅
Solution:
- The live Tarkov files you copied were outdated. Delete any folders of Tarkov present and re-install via the official launcher provided by Battlestate Games.

### Detected faulty json ✅
Solution:
- A JSON file provided by SPT is faulty or has syntax errors. Download and use Visual Studio Code/Codium and open said JSON file with it, it will show you what needs to be fixed.

### Patcher won't work ✅
Solution:
- You're likely missing .NET frameworks required for the application to work. Download the following two frameworks:

  [.NET 4.7.2 Developer Pack Installer](https://dotnet.microsoft.com/en-us/download/dotnet-framework/thank-you/net472-developer-pack-offline-installer)

  [Runtime Desktop 6.0.4 Windows x64 Installer](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-6.0.4-windows-x64-installer)
