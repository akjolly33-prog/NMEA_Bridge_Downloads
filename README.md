# NMEA Bridge – Downloads

NMEA Bridge reads NMEA 0183 data from a GPS receiver on one serial port, corrects the
date in `$--ZDA` sentences (+7168 days, GPS week-rollover fix) and retransmits the
stream on a second serial port at 9600 baud.

## ⬇ Download

**[Download the latest installer (NMEA_Bridge_Setup.exe)](https://github.com/akjolly33-prog/NMEA_Bridge_Downloads/releases/latest/download/NMEA_Bridge_Setup.exe)**

Previous versions and release notes: [Releases](https://github.com/akjolly33-prog/NMEA_Bridge_Downloads/releases)

## Install

1. Run `NMEA_Bridge_Setup.exe` – no administrator rights needed.
   If Windows SmartScreen appears, click **More info → Run anyway**.
2. The app is installed to `%APPDATA%\NMEA Bridge` with a desktop shortcut.

## Activate your license

1. On first start the app runs in **Demo Mode** and shows your **Hardware ID**.
2. Send a screenshot of that Hardware ID window to your distributor.
3. You will receive a `license.dat` file. Copy it into
   `%APPDATA%\NMEA Bridge\assets` (paste that path into Explorer's address bar).
4. Restart the app – the status bar shows **Activated: &lt;your name&gt;**.

Without a license the app runs in Demo Mode (simulated data only).

## Requirements

Windows 10 or 11 (64-bit), two serial/USB-serial ports.

## Support

mail@oceanscience.in – please include your Hardware ID and licensee name.
