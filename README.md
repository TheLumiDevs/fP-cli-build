> [!CAUTION]
> NOT WORKING AS WELL, IT NEEDS REWRITING.

# fP-Cli-Build
Auto CLI build fakeProfile plugin for Vencord, Equicord, etc...

**Current fork version:**

Vencord: ![](https://img.shields.io/github/package-json/v/Vendicated/Vencord?style=for-the-badge&logo=github&logoColor=d3869b&label=&color=1d2021&labelColor=282828) Equicord: ![](https://img.shields.io/github/package-json/v/Equicord/Equicord?style=for-the-badge&logo=github&logoColor=00ffff&label=&color=1d2021&labelColor=282828)

# Status
> [!NOTE]
> - Extension & Userscript has been moved to new repository is **[fP-extension-build](https://github.com/TheLumiDevs/fP-extension-build)**. If you want update and download new extension, please go to new repository. Thank you <3  

**Vencord:**  
> - ~~Chrome extension: ✅~~  
> - ~~Firefox extension: ✅~~  
> - ~~Userscript: ✅~~  
> - Windows CIL Installer: ❌
> - Linux CIL Installer: ❌
> - macOS CIL Installer: ❌  

**Equicord:**
> - ~~Chrome extension: ✅~~  
> - ~~Firefox extension: ✅~~  
> - ~~Userscript: ✅~~  

# How to use
> [!NOTE]
> This project is in under development, it can maybe changed. This project not completed yet.

- Required: [Git(for cloning)](https://git-scm.com/downloads); [Node JS](https://nodejs.org/en/download/); [pnpm](https://pnpm.io/installation)

- Clone this repository by terminal and go to cloned repository:
```shell
https://github.com/TheLumiDevs/fP-Auto-build.git
cd fP-Auto-Build/
```

> [!IMPORTANT]
> After choosing build, do for sure these commands:
> ```shell
> pnpm i --no-frozen-lockfile
> ```
> Because there's no gurantees that it will work without these commands perfectly.

- Now you need choose build folder which client you prefer using:
    - You can use `Vencord/` or any build folder like `Equicord/` for default Discord. But you need do `pnpm inject` command for injecting your default Discord, **make sure that you closed your default Discord fully**.
    - For custom desktop client such like as **Vesktop** or **Equibop** you need choose specific folder:
        - For **Vesktop** users needs `Vencord/` folder.
        - For **Equibop** users needs `Equibop/` folder.
    1. After choosing open custom desktop client settings, ex. `Vesktop Settings`.
    2. Scroll to the end and click `Open Developer Settings`.
    3. In `dist/` choose folder with any OS from your build folder, it will be `dist-OS/dist-OS` (don't ask why it is twiced) and reload desktop client fully. Enjoy.
