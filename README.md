# GrapheneOS
Setup for the GrapheneOS environment.
> Last updated: version [2024020500](https://grapheneos.org/releases#2024020500).

## Installation
1. Follow the instructions from [grapheneos.org](https://grapheneos.org).
2. Complete the setup with minimal permissions granted.

## Settings
* Network & internet
    * Internet
        * SIM (⚙️)
            * ✅ Use SIM
            * ✅ Mobile data
            * ❌ Roaming
            * 📝 Data warning & limit
            * ✅ VoLTE
            * 📝 Preferred network type - 5G (recommended)
            * Wi-Fi calling
                * ✅ Use Wi-Fi calling
                * 📝 Calling preference - Call over Wi-Fi
                * 📝 Roaming preference - Wi-Fi
            * ✅ Carrier video calling
            * ✅ Automatically select network
            * ✅ Allow 2G
            * ✅ Vo5G
        * ✅ Wi-Fi
            * 📝 Connect to a network
        * Network preferences
            * ❌ Turn on Wi-Fi automatically
            * ❌ Notify for public networks
            * 📝 Turn off Wi-Fi automatically - Never
    * ❌ Airplane mode
    * ❌ Hotspot & tethering
        * ❌ Wi-fi hotspot
        * ❌ USB tethering
        * ❌ Bluetooth tethering
        * ❌ Ethernet tethering
    * ✅ Data Saver
    * 📝 Private DNS - Automatic
    * 📝 Internet connectivity checks - GrapheneOS server
    * 📝 Attestation key provisioning - Enabled (GrapheneOS proxy)
    * 📝 Widevine provisioning - Enabled (GrapheneOS proxy)
* Connected Devices
    * Connection preferences
        * Bluetooth
            * ❌ Use Bluetooth
            * 📝 Turn off Bluetooth automatically - 1 minute
        * NFC
            * ❌ Use NFC
            * ✅ Require device unlock for NFC
        * Printing
            * Default Print Service
                * ❌ Use print service
        * ❌ Ultra-Wideband (UWB)
* Apps
    * See all apps
        * For each app:
            * 📝 Disable all permissions except "Notifications"
            * 📝 Disable "Background data"
            * 📝 Enable "Pause app activity if unused"
        * Apps:
            * 📝 Enable "Network"
    * Special app access
        * Modify system settings
            * 📝 Disable all apps
        * ❌ Special access to hardware accelerators for Google apps
* Notifications
    * Notification history
        * ❌ Use notification history
    * Bubbles
        * ✅ Allow apps to show bubbles
    * 📝 Notifications on lock screen - Hide silent conversations and notifications
    * ❌ Sensitive notifications
    * ❌ Do Not Disturb
    * ❌ Flash notifications
    * ✅ Wireless emergency alerts
        * 📝 Alert reminder - Once
    * ❌ Hide silent notifications in status bar
    * ❌ Allow notification snoozing
    * ✅ Notification dot on app icon
    * ✅ Enhanced notifications
* Battery
    * Battery Saver
        * ✅ Use Battery Saver
        * 📝 Set a schedule - 20%
        * ❌ Turn off at 90%
    * ✅ Battery percentage
    * ❌ Battery share
* Display
    * ✅ Adaptive brightness
    * Lock screen
        * 📝 Privacy - Show sensitive content only when unlocked
        * ❌ Use device controls
        * ✅ Dynamic clock
        * ❌ Always show time and info
        * Tap to check phone
            * ✅ Tap to check phone
        * Lift to check phone
            * ✅ Lift to check phone
        * ✅ Wake screen for notifications
    * 📝 Screen timeout - 1 minute
    * ❌ Dark theme
    * ❌ Night Light
    * 📝 Colors - Adaptive
    * ✅ Auto-rotate screen
    * 📝 Screen resolution - High resolution
    * ✅ Smooth Display
    * ❌ Increase touch sensitivity
    * ✅ Screen saver
* Wallpaper & style
    * ✅ Show notifications on the lock screen
* Security
    * 📝 Screen lock - PIN (⚙️)
        * ✅ Enhanced PIN privacy
        * 📝 Lock after screen timeout - Immediately
        * ✅ Power button instantly locks
    * 📝 Fingerprint Unlock
        * ✅ Use for screen unlocking
    * 📝 Auto reboot - 72 hours
    * 📝 USB peripherals - Allow new USB peripherals when unlocked
    * Secure app spawning
        * ✅ Use secure app spawning
    * ✅ Automatic exploit protection compatibility mode
    * Memory tagging in third-party apps
        * ✅ Enable by default
    * Native code debugging
        * ✅ Block for third-party apps by default
    * ❌ Scramble PIN input layout
    * ✅ Allow camera access when the device is locked
    * ❌ Notify about system process crashes
    * More security settings
        * SIM lock
            * ❌ Lock SIM
        * App pinning
            * ❌ Use app pinning
        * ✅ Confirm SIM deletion
* Privacy
    * ❌ Camera access
    * ❌ Microphone access
    * ❌ Allow Sensors permission to apps by default
    * ❌ Save screenshot timestamp to EXIF
    * ❌ Show passwords
    * 📝 Notifications on lock screen - Show sensitive content only when unlocked
    * ✅ Show mesdia on lock screen
    * ✅ Show clipboard access
* Location
    * ❌ Use location
    * Location services
        * Wi-Fi scanning
            * ❌ Wi-Fi scanning
        * Bluetooth scanning
            * ❌ Bluetooth scanning
    * 📝 Secure User Plan Location (SUPL) - Enabled (GrapheneOS proxy)
    * 📝 Predicted Satellite Data Service (PSDS) - Enabled (GrapheneOS server)
* Passwords & accounts
    * ❌ Automatically sync app data
* System
    * Languages
        * Regional preferences
            * 📝 Temperature - Celsius (°C)
            * 📝 First day of week - Sunday
    * Gestures
        * Quickly open camera
            * ✅ Quickly open camera
        * 📝 Navigation mode - Gesture navigation
        * One-handed mode
            * ❌ Use one-handed mode
        * Tap to check phone
            * ✅ Tap to check phone
        * Lift to check phone
            * ✅ Lift to check phone
        * ✅ Prevent rignging - Vibrate
    * Date & time
        * ✅ Set time automatically
        * ✅ Set automatically
        * ❌ Use locale default
        * ✅ Use 24-hour format
    * System update
        * 📝 Release channel - Stable
        * 📝 Permitted networks - Unmetered
        * ✅ Require battery above warning level
        * ❌ Require device to be charging
        * ❌ Automatic reboot
    * Multiple users
        * ✅ Allow multiple users
        * Users
            * 📝 Owner (red)
            * 📝 Main (blue)
                * ❌ Allow running in the background
                * ❌ Turn on phone calls & SMS
                * 📝 App installs and updates - Enabled
            * 📝 Finance (green)
                * ❌ Allow running in the background
                * ❌ Turn on phone calls & SMS
                * 📝 App installs and updates - Enabled
            * 📝 Social (orange)
                * ❌ Allow running in the background
                * ❌ Turn on phone calls & SMS
                * 📝 App installs and updates - Enabled
            * 📝 Google (yellow)
                * ❌ Allow running in the background
                * ❌ Turn on phone calls & SMS
                * 📝 App installs and updates - Enabled
            * 📝 Private (purple)
                * ❌ Allow running in the background
                * ❌ Turn on phone calls & SMS
                * 📝 App installs and updates - Enabled
        * ✅ Delete guest activity
        * ❌ Allow guest to make phone calls
        * ✅ Send notifications to current user
* Home screen
    * Notification bar
        * Internet | Auto-rotate
        * Location | Airplane mode
        * Screen record | Flashlight
        * Camera access | Mic access
        * Battery Saver | Data Saver
    * Home settings
        * 📝 Notification dots - On
        * ❌ Add app icons to home screen
        * ❌ Allow home screen rotation
  * Application settings
      * 📝 Update the settings for each application

## Users
### Owner
The admin profile for creating other user profiles. Should not be used for anything besides alarms, sending texts, and making phone calls. Data on other profiles can be purged by deleting the profile itself, but data on the owner profile cannot be deleted without a factory reset.

* Set alarms
* Enable the following application permissions:
    * Contacts: Allow "Contacts", "Phone"
    * Messaging: Allow "Contacts", "Phone", "SMS"
    * Phone: Allow "Call logs", "Contacts", "Phone"

### Main
The main profile for browsing the web, taking photos and videos, and using FOSS applications.

* Install and/or enable the following application permissions:
    * AndBible
    * Clima: +Network
    * Camera: +Camera, +Microphone, +Sensors
    * FTPClient: +Network
    * Gallery: +Photos and Videos Storage Scopes (photo directory, screenshot directory, screen record directory)
    * LibreTube: +Network
    * Neo Store: +Network
    * Notally
    * OsmAnd: +Network, -Memory tagging
    * Vandium: +Network

### Finance
The profile for using personally identifiable applications.

* Install and/or enable the following application permissions:
    * Banking: +Network
    * Phone: +Network

### Social
The profile for using non-FOSS applications.

* Install and/or enable the following application permissions:
    * Socials: +Network
    * Uber: +Network

### Google
The profile for running Google Play services.

* Install and/or enable the following application permissions:
    * Google Play services

### Private
The profile for all other applications.
