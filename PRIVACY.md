# Privacy Policy

Last updated: October 21, 2026

Smart Island processes information on your Android device to show notifications and system activity in its floating island. Some optional features use the internet. This policy describes what the app reads, stores, and sends.

## Information the app processes

If you grant notification access, the app reads notification details such as the sending app, title, text, icons, actions, and call or media status. It uses accessibility access to identify foreground app windows and handle selected interface actions; it does not need to read the text displayed inside other apps for the island overlay. Overlay access displays the island above other apps.

The app also processes settings and, when you use the relevant features, calendar events, approximate location, network status, and Bluetooth device information.

## Network requests

The app does not include advertising or analytics SDKs and does not send notification content to its servers. Network requests are used for these features:

- The About and update screens request public release, contributor, commit, and repository information from GitHub. These requests identify the app through a fixed user agent and do not include notification contents or account credentials.
- Weather lookups send coordinates rounded to one decimal place (about 10 km) to Open-Meteo, or to the custom HTTPS weather service you configure. If automatic location is selected and a recent location is unavailable, the app may query an IP geolocation provider; that provider receives the network request and can see your IP address.
- When the VPN status card needs a city label, the app may query an IP geolocation service through the VPN network. That service can see the VPN network's public IP address.

External links open GitHub, email, or social pages in another app or browser. Those services have their own privacy practices.

## Storage and retention

Island settings and weather cache data are stored locally. Notification history is off by default; if you enable it, notification details are stored locally for the retention period selected in the app. Diagnostic reports are generated only when you choose to export them. They include device and app details, settings, recorded diagnostic logs, and process logcat, so review a report before sharing it.

The app does not intentionally upload notification content. Keep in mind that Android backup or device-transfer behavior may depend on your Android version and device settings.

## Your controls

You can disable Smart Island, revoke its overlay or notification access, turn off notification history, disable optional weather or VPN location features, clear app storage, or uninstall the app. Android may request additional access for optional features such as calendar, location, or Shizuku-based system integrations.

## Contact

For privacy questions, open an issue in this repository without including private notification content, diagnostic reports, or secrets.
