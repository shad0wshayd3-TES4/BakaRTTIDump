# CommonLibOB64 Plugin Template

This is a basic plugin template using CommonLibOB64.

### Requirements
* [XMake](https://xmake.io) [2.8.2+]
* C++23 Compiler (MSVC, Clang-CL)

## Getting Started
You can use the "Use this template" button on GitHub to create your own repo pre-configured with the project name set to your repo name.
Alternatively, you can clone this repo manually:
```bat
git clone --recurse-submodules https://github.com/shad0wshayd3-TES4/commonlibob64-template
cd commonlibob64-template
```

### Build
To build the project, run the following command:
```bat
xmake build
```

> ***Note:*** *This will generate a `build/windows/` directory in the **project's root directory** with the build output.*

### Build Output (Optional)
If you want to redirect the build output, set one of or both of the following environment variables:

- Path to an Oblivion Remastered install folder: `XSE_OBR_GAME_PATH`

- Path to a Mod Manager mods folder: `XSE_OBR_MODS_PATH`

### Project Generation (Optional)
If you want to generate a Visual Studio project, run the following command:
```bat
xmake project -k vsxmake
```

> ***Note:*** *This will generate a `vsxmakeXXXX/` directory in the **project's root directory** using the latest version of Visual Studio installed on the system.*

### Upgrading Packages (Optional)
If you want to upgrade the project's dependencies, run the following commands:
```bat
xmake repo --update
xmake require --upgrade
```
