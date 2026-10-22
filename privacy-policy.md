# Privacy Policy — Islamic Prayer Times (Zepp OS)

**Last updated: October 22, 2026**

## Summary

Islamic Prayer Times is a Mini Program for Zepp OS smartwatches. It calculates the five daily prayer times and sunrise on the watch itself, from your position or a city you choose, and can alert you before each prayer. All calculation happens on the watch. The app has no internet access, no companion phone component, no analytics and no tracking. The developer does not collect, receive, store, or sell any of your data.

## What the app reads

- **Location.** Your position is used for one purpose: the sun's position over you decides prayer times. You can get it in one of two ways:
  - **GPS** (default): the app asks the watch for a single satellite fix when it opens, then turns GPS off again. The latitude and longitude are used for the calculation and kept on the watch, so the next launch can show times straight away.
  - **A chosen city**: you pick a city from a list built into the app. While a city is chosen, GPS is not used at all.
- **Time and time zone**, read from the watch's clock to place the prayer times in your day.
- **Device information**: the screen size and shape, used to lay out the screens. Nothing that identifies you or your watch is read.

## What the app stores

Everything is stored only on the watch, in the app's own local storage:

- Your last GPS position (latitude and longitude, and the name of the nearest city in the built-in list, if one is within 60 km), or the city you chose.
- Your settings: calculation method, Asr method, high-latitude rule, manual time adjustments, alert choices, time format, name script, color theme, night dimming and countdown display.
- Bookkeeping for alerts: the identifiers and times of the alarms the app has set, so it can update or cancel them.

## Alerts

Prayer alerts use the watch's own system alarm service. The app sets an alarm for each prayer you turned alerts on for; when one goes off, the watch opens the app, shows the prayer and vibrates. Alerts are off until you turn them on, and each can be switched off in the app's settings. Nothing about an alert leaves the watch.

## Network and sharing

The app makes **no network requests**. It has no server, no phone-side service, and no third-party SDKs. Your location and settings never leave the watch through this app.

The app is installed and updated through the Zepp app on your phone. Zepp Health handles that installation under its own privacy policy; the developer receives no information from it about you.

## Permissions

| Permission | Why |
|---|---|
| `device:os.geolocation` | Get a GPS fix for prayer-time calculation, unless you chose a city |
| `device:os.alarm` | Set the prayer alerts you turned on |
| `device:os.local_storage` | Keep your settings and last position on the watch |
| `data:os.device.info` | Read the screen size to lay out the app |

## What we do NOT do

- We do not collect, transmit, sell, or share any personal data.
- We do not send your location anywhere, or keep a history of where you have been. Only the most recent position is kept, on the watch, and a newer one replaces it.
- We do not use analytics, telemetry, advertising, or third-party SDKs.
- We do not operate any server that receives your data.

## Your control

You can choose a city instead of GPS (Settings → Location), and switch back with "Use GPS instead". Uninstalling the app from the watch removes all of its stored data.

## Children

The app does not knowingly collect information from anyone, including children, because it collects no information at all.

## Changes to this policy

If this policy changes, the updated version will be published at this same address with a revised "Last updated" date.

## Contact

Questions or concerns: open an issue in this repository, or email **fullscreendev@gmail.com**.

## About the developer

Islamic Prayer Times is built by the team behind [TechStoriesIndia.com](https://techstoriesindia.com/), covering tech news, launches and how-tos, and [TechStoriesIndia.in](https://techstoriesindia.in/), covering gadget launches, specs and buying guides.

---

*Islamic Prayer Times is an independent app. It is not affiliated with, endorsed by, or sponsored by Zepp Health or Amazfit. "Zepp" and "Amazfit" are trademarks of Zepp Health Corporation, used here only to describe the watches the app runs on.*
