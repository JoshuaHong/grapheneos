# GrapheneOS
Setup for the GrapheneOS environment.
> Last updated: version [2025120400](https://grapheneos.org/releases#2025120400).

## Installation
1. Follow the instructions from [grapheneos.org](https://grapheneos.org).
2. Complete the setup with minimal permissions granted.

## Settings
* Network & internet
    * Internet
        * ✅ Use Wi-Fi
            * 📝 Connect to a network
        * Network preferences
            * ❌ Turn on Wi-Fi automatically
            * ❌ Notify for public networks
            * ✅ Allow WEP networks
    * SIMs
        * SIM
            * ✅ Use this SIM
            * ❌ Roaming
            * 📝 Data warning & limit
            * ✅ VoLTE
            * 📝 Preferred network type - 5G (recommended)
            * Wi-Fi calling
                * ✅ Use Wi-Fi calling
                * 📝 Calling preference - Call over mobile network
                * 📝 Roaming preference - Wi-Fi
            * ✅ Automatically select network
            * ❌ 2G network protection
        * ✅ Mobile data
    * ✅ eSIM support
    * ❌ Airplane mode
    * Hotspot & tethering
        * ❌ Wi-fi hotspot
        * ❌ USB tethering
        * ❌ Bluetooth tethering
        * ❌ Ethernet tethering
    * Data Saver
        * ✅ Use Data Saver
    * VPN
        * VPN (⚙️)
            * ✅ Always-on VPN
            * ❌ Block connections without VPN
    * 📝 Private DNS - Automatic
    * 📝 Internet connectivity checks - GrapheneOS server
    * 📝 Mobile network security
    * 📝 Attestation key provisioning - Enabled (GrapheneOS proxy)
    * 📝 Widevine provisioning - Enabled (GrapheneOS proxy)
* Connected Devices
    * Connection preferences
        * Bluetooth
            * ❌ Use Bluetooth
            * ❌ Automatically turn on tomorrow
        * Audio sharing
            * ❌ Share audio
        * NFC
            * ❌ Use NFC
            * ✅ Require device unlock for NFC
        * Thread
            * ❌ Use Thread
        * Connected Cameras
            * ❌ Use Connected Cameras
        * Printing
            * Default Print Service
                * ❌ Use print service
        * ❌ Ultra-Wideband (UWB)
* Apps
    * See all apps
        * For each app:
            * 📝 Disable all permissions
            * ✅ Enable "Notifications"
            * ✅ Manage app if unused
    * Special app access
        * Modify system settings
            * 📝 Disable all apps
        * Special access to hardware accelerators for Google apps
            * ❌ Grant special access to hardware accelerators for Google apps
* Notifications
    * Notification history
        * ❌ Use notification history
    * Bubbles
        * ✅ Allow apps to show bubbles
    * Notifications on lock screen
        * ✅ On
        * 📝 Compact view
        * ✅ Show viewed notification icons
        * ❌ Show silent notifications
        * ❌ Show sensitive content
    * Notification cooldown
        * ✅ Use notification cooldown
    * Flash notifications
        * ❌ Camera flash
        * ❌ Screen flash
    * Wireless emergency alerts
        * ✅ Allow alerts
        * 📝 Alert reminder - Once
    * ❌ Hide silent notifications in status bar
    * ❌ Allow notification snoozing
    * ✅ Notification dot on app icon
    * ✅ Enhanced notifications
* Display
    * ✅ Adaptive brightness
    * Lock screen
        * ❌ Use device controls
        * ✅ Dynamic clock
        * Tap to check phone
            * ✅ Tap to check phone
        * Lift to check phone
            * ✅ Lift to check phone
        * ✅ Wake screen for notifications
    * ❌ Always-on display
    * 📝 Screen timeout - 1 minute
    * ❌ Dark theme
    * ❌ Night Light
    * 📝 Colors - Natural
    * ✅ Auto-rotate screen
    * 📝 Screen resolution - High resolution
    * ✅ Adaptive tone
    * ✅ Smooth display
    * ❌ Screen protector mode
    * Screen saver
        * ✅ Use screen saver
* Battery
    * Battery Saver
        * ❌ Use Battery Saver
        * 📝 Set a schedule - 20%
        * ✅ Turn off at 90%
    * Battery Manager
        * ✅ Use Battery Manager
    * Charging optimization
        * ✅ Limit to 80%
    * ✅ Battery percentage
* System
    * Language & region
        * Temperature
            * 📝 Celsius (°C)
        * Measurement system
            * 📝 Metric
        * First day of week
            * 📝 Sunday
    * Keyboard
        * On-screen keyboard
            * ❌ Keyboard
            * ✅ FUTO Keyboard
        * Spell checker
            * ✅ Use spell checker
    * Gestures
        * Double press power button
            * ✅ Use double press
            * 📝 Camera
        * Navigation mode
            * 📝 Gesture navigation
        * One-handed mode
            * ❌ Use one-handed mode
            * ❌ One-handed mode shortcut
        * Tap to check phone
            * ✅ Tap to check phone
        * Lift to check phone
            * ✅ Lift to check phone
        * ✅ Prevent rignging
            * 📝 Vibrate
    * Date & time
        * ✅ Automatic date and time
        * ✅ Automatic time zone
        * ✅ Use 24-hour format
    * System updates
        * 📝 Release channel - Stable
        * ✅ Receive security preview releases
        * 📝 Permitted networks - Unmetered
        * ✅ Require battery above warning level
        * ❌ Require device to be charging
        * ❌ Automatic reboot
    * Users
        * ✅ Allow user switch
        * Users
            * 📝 Owner (red)
            * 📝 Google (yellow)
                * ❌ Allow running in the background
                * ❌ Turn on phone calls & SMS
                * 📝 App installs and updates - Enabled
                * 📝 Install available apps
                    * Aurora Store
                    * FTPClient
                    * Google Play services
                    * Google Play Store
                    * Orbot
            * 📝 Private (blue)
        * ✅ Delete guest activity
        * ❌ Allow guest to make phone calls
        * ✅ Send notifications to current user
* Security & privacy
    * Device unlock
        * Screen lock
            * 📝 PIN
            * ❌ Scramble PIN layout
            * ✅ Enhanced PIN privacy
            * ✅ Allow camera access when locked
            * 📝 Lock after screen timeout - Immediately
            * ✅ Power button instantly locks
        * Fingerprint
            * ✅ Unlock your phone
            * ✅ Verify it's you in apps
    * Privacy controls
        * ❌ Camera access
        * ❌ Microphone access
        * ✅ Show clipboard access
        * ✅ Show passwords
        * Location access
            * ❌ Use location
            * Location services
                * Wi-Fi scanning
                    * ❌ Wi-Fi scanning
                * Bluetooth scanning
                    * ❌ Bluetooth scanning
                * Network location
                    * ❌ Off
                * Geocoder
                    * ❌ Off
            * Secure User Plan Location (SUPL)
                * 📝 GrapheneOS proxy
            * Predicted Satellite Data Service (PSDS)
                * 📝 GrapheneOS server
    * Exploit protection
        * Auto reboot
            * 📝 72 hours
        * USB-C port
            * 📝 Off
        * Turn off Wi-Fi automatically
            * 📝 Never
        * Turn off Bluetooth automatically
            * 📝 1 minute
        * Memory tagging
            * ❌ Enable by default
        * Native code debugging
            * ❌ Block for third-party apps by default
        * WebView JIT
            * ❌ Disable for third-party apps by default
        * Dynamic code loading via memory
            * ❌ Restrict for third-party apps by default
        * Dynamic code loading via storage
            * ❌ Restrict for third-party apps by default
        * Secure app spawning
            * ✅ Use secure app spawning
    * More security & privacy
        * ✅ Show media on lock screen
        * ❌ Allow Sensors permission to apps by default
        * ❌ Save screenshot timestamp to EXIF
        * Mobile network security
            * ❌ Network notifications
            * ❌ 2G network protection
        * SIM lock
            * ❌ Lock SIM
        * App pinning
            * ❌ Use app pinning
        * ❌ Notify about system process crashes
        * ✅ Automatic exploit protection compatibility mode
* Passwords, passkeys & accounts
    * ❌ Automatically sync app data
 
## Home screen
 * Notification bar
     * Internet | Auto-rotate
     * Bluetooth | Location
     * Screen record | Flashlight
     * Camera access | Mic access
     * Battery Saver | Data Saver
 * Home settings
     * 📝 Notification dots - On
     * ❌ Add app icons to home screen

## Apps
* App store: Network, Notifications
    * Google Play services: Sensors
    * Google Play Store: Disable
    * Thermometer: Camera (Allow only while using the app), Sensors
* Camera: Camera (Allow only while using the app), Microphone (Allow only while using the app), Notifications, Sensors
* Contacts: Call logs, Contacts, Notifications, Phone
* Gallery: Disable
* Messaging: Disable
* [Obtanium](https://github.com/ImranR98/Obtainium): Allow from this source, Network, Notifications
    * [AnkiDroid](https://github.com/ankidroid/Anki-Android): All files access (Storage Scopes), Network, Notifications
    * [Aurora Store](https://gitlab.com/AuroraOSS/AuroraStore): Allow from this source, Allow access to Android/obb folder, Network, Notifications
        * Google Maps: Location (Allow only while using the app, Use precise location), Network, Notifications
        * Google Translate: Notifications
        * Literal Word: Notifications
    * [Auxio](https://github.com/OxygenCobalt/Auxio): Music and audio (Storage Scopes), Notifications
    * [Breezy Weather](https://github.com/breezy-weather/breezy-weather): Network, Notifications
    * [Fossify Calendar](https://github.com/FossifyOrg/calendar): Notifications
    * [Fossify Gallery](https://github.com/FossifyOrg/Gallery): Notifications, Photos and videos (Storage Scopes)
    * [Fossify Messages](https://github.com/FossifyOrg/Messages): Contacts, Notifications, Phone, SMS
    * [Fossify Notes](https://github.com/FossifyOrg/Notes):
    * [FTPClient](https://codeberg.org/qwerty287/ftpclient): Network, Nearby devices
    * [FUTO Keyboard](https://github.com/futo-org/android-keyboard): Notifications
    * [KeePassDX](https://github.com/Kunzisoft/KeePassDX): Notifications
    * [LibreTube](https://github.com/libre-tube/LibreTube): Network, Notifications
    * [Metrolist](https://github.com/mostafaalagamy/Metrolist): Network, Notifications
    * [Neo Store](https://github.com/NeoApplications/Neo-Store): Network, Notifications
    * [Open Video Editor](https://github.com/devhyper/open-video-editor):
    * [Orbot](https://github.com/guardianproject/orbot-android): Network
    * [ScreenStream](https://github.com/dkrivoruchko/ScreenStream): Notifications
    * [Thunderbird](https://github.com/thunderbird/thunderbird-android): Network, Notifications
    * [YTDLnis](https://github.com/deniscerri/ytdlnis): Network, Notifications
* Phone: Call logs, Contacts, Notifications, Phone
* Vanadium: Network, Notifications
