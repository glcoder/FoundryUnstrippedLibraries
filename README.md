# FoundryUnstrippedLibraries

Non-stripped [Foundry Demo](https://www.paradoxinteractive.com/games/foundry/about) libraries to run BepInEx (or alternative loader).

## Install

* Download [latest archive](https://github.com/glcoder/FoundryUnstrippedLibraries/releases/latest).
* Locate Foundry installation direcotry (Steam -> Foundry -> Browse Local Files).
* Create `UnstrippedLibraries` folder in Foundry installation directory and unpack all libraries from archive there.
* Download latest [BepInEx 5 x64](https://github.com/BepInEx/BepInEx/releases/latest).
* Unpack BepInEx into Foundry installation directory.
* In `doorstop_config.ini` set:

```ini
dllSearchPathOverride=UnstrippedLibraries
```

## Uninstall

* Remove all files unpacked during installation.
