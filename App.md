# Dev Resources: App

## Technologies

### TODO
* Which Platform(s) to stream connection to (Windows/Android) -> Android has better documented [API](https://developer.android.com/guide/topics/connectivity/wifip2p)

### Wifi-Direct
* [Wifi-Direct on Linux](https://www.youtube.com/watch?v=5BkfztZ0pOE).
  * *NOTE*: Only on Rasp-PI. On Ubuntu -> see wpa_supplicant & wpa_cli

* [Wifi-Direct via Library](https://w1.fi/wpa_supplicant/devel/p2p.html)
  * [API](https://w1.fi/wpa_supplicant/devel/p2p_8h.html)

### Tech-Stack: Core/Back-End
* [MIDI for footswitch](https://docs.rs/midir/0.8.0/midir/)
* [Wifi-Direct on Windows](https://docs.microsoft.com/en-us/uwp/api/Windows.Devices.WiFiDirect?redirectedfrom=MSDN&view=winrt-22621)

* **Note**: Windows does support Wifi-P2P (not found in `netsh show drivers`, but in `netsh wlan show wirelesscapabilities` command). Test connection once set up. If not supported, fallback on same network connection??. 
  
* **NOTE**: WSL doesn't have access to WIFI hardware, thus WSL-Wifi-Direct will not work

### Tech-Stack: Front-End

* [Tauri](https://tauri.studio/) sits in the back end of the App.
* [Vite](https://vitejs.dev/) as FrontEnd JS buildtooling
* [Svelte](https://svelte.dev/) as FrontEnd UI framework
* [Tailwind CSS](https://tailwindcss.com/) for UI styling
* [Daisy UI](https://daisyui.com/components/textarea/) (Tailwind based component library)
* [Svelte Material UI](https://sveltematerialui.com/)

### UI-Design Guidelines

* [Material IO](https://material.io/). Unter [Components](https://material.io/components?platform=web) gibts auch Web-Components.

* [Guide to Dark Themes with Material Design](https://blog.prototypr.io/how-to-design-a-dark-theme-for-your-android-app-3daeb264637)

## Architecture