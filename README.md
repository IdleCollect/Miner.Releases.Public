# Miner.Releases.Public
Public releases of IdleCollect's miner application.

## Release Notes

### 1.1.0 (protocol 1)
* **Added** an auto updater! You will need to re-download the app to get access to these new fixes, but our auto updater should take care of that in future versions.
* **Added** automatic error detection, meaning if there's an issue with IdleCollect on your PC (antivirus issue, incompatible GPU), we will tell you.
* **Added** animation for mining, to make it more clear when the miner is active.
* **Added** real-time earning estimations, which gets synced with real values periodically.
* **Added** functionality for IdleCollect to automatically apply a Windows Defender whitelist exception.
* **Added** a new tips section, which lets us give you tips for how to maximize your profits (WIP).
* **Added** weekly emails to show how much you earned over the week/month, and in what areas you can improve your profits.
* **Added** a minimize button (automatic minimization was not changed).
* **Added** on-boarding screens, which is basically just a one-time tutorial when you first use the app, showing you all the basics and how to use IdleCollect.
* **Added** functionality to estimate your profits based on your GPU setup
* **Fixed** an issue where mining speed (MH/s) would go to 0 when switching windows
* **Fixed** an issue where mining speed (MH/S) going to 0 for falsely detecting game activity.
* **Fixed** an issue where your hashrate was sometimes misreported (e.g.: reporting 15.54 MH/s as 1554 MH/s).
* **Fixed** an issue where the application was not minimizing when de-selected.
* **Upgraded** analytics engine, which will allow us to make better decisions on what to change/improve and also what coins are optimal for you to mine.
* **Upgraded** estimation service, gives accurate estimation of earning.
* **Reworked** our backend messaging layer, this allows us to more accurately push out sync requests.


### 1.0.0 (protocol 1)
* **Initial release**, nothing to report for changes.
