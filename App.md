# Dev Resources: App

## Technologies

### Tech-Stack: Core/Back-End

* [Service Discovery on same network](https://crates.io/crates/mdns)
* [MIDI for footswitch](https://docs.rs/midir/0.8.0/midir/)
* [Wifi-Direct on Linux](https://www.youtube.com/watch?v=5BkfztZ0pOE). 

* **Note**: Windows does support Wifi-P2P (not found in `netsh show drivers`, but in `netsh wlan show wirelesscapabilities` command). Test connection once set up. If not supported, fallback on same network connection??. 
  
* **NOTE**: WSL doesn't have access to WIFI hardware, thus WSL-Wifi-Direct will not work

### Tech-Stack: Web Based Front-End

* [Tauri](https://tauri.studio/) sits in the back end of the App. Handles USB/MIDI connections
* [Vite](https://vitejs.dev/) as FrontEnd JS buildtooling
* [Svelte](https://svelte.dev/) as FrontEnd UI framework
* [Tailwind CSS](https://tailwindcss.com/) for UI styling
* [Daisy UI](https://daisyui.com/components/textarea/) (Tailwind based component library)

### UI-Design Guidelines

* [Material IO](https://material.io/). Unter [Components](https://material.io/components?platform=web) gibts auch Web-Components.

* [Guide to Dark Themes with Material Design](https://blog.prototypr.io/how-to-design-a-dark-theme-for-your-android-app-3daeb264637)

## Architecture