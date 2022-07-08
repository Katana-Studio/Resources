# Notes

## Katana-Patches
Using pre-made katana patches will not be supported, since commonly, third-party patches are optimised for the creators gear, which in most cases results in the patch not satisfying the consumers needs.  
However, creation of custom patches is supported, though they will not be exportable, since they're stored in a custom file format (TOML-Format) which will be readable for Katana-Studio.

## Control from Panel vs Control from App-UI vs Controll from Remote App-UI

Disable touch response on ui elements if Katana is controlled from the panel. Show popup dial which displays current parameter controlled by katana panel / hint that other control source is being used.

## Variable Value Dial

* Add *pan* button to automatically let value on dial go from 0..MAX -> easier tone testing / discovery

## Quick Access Page

Supply a quick access page with user customisable contens (quick access for boost lvl / gain lvl / ...)

## Custom UI keyboard

Supply custom keyboard for user input in the UI

## Screen Brightness

* [Control Screen brightness from commandline](https://askubuntu.com/questions/149054/how-to-change-lcd-brightness-from-command-line-or-via-script)

## Tauri: Auto Updates

* [Auto Updates via GitHub Releases](https://github.com/tauri-apps/tauri/discussions/2776). Reads JSON from Github gist.
    Maybe create CI/CD Task & create new release gist on release being pushed to main/release branch
* [Tauri Update API guide](https://tauri.app/v1/guides/distribution/updater/)

## Tailwind VSCode
* [Collapsable style thingys](https://www.youtube.com/shorts/4VUaoUAaMQg)