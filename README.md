<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12&height=180&section=header&text=Vishwanath%20Sanapur&fontSize=42&fontColor=ffffff" width="100%"/>
</div>

```
vishwanath@GSKSJTI:~$ whoami
```

```
OS   : Pop!_OS 22.04 → 24.04
Editor : nano
Studies : CSE @ GSKSJTI Bengaluru, VTU — 4th yr / 7th sem
Doing : maintaining cosmic-connect + cosmic-power-monitor + the speed monitor
GitHub : this is acc #2, first one (Smb1234567) got shadowbanned
```

CSE student who's more interested in breaking things than the syllabus. Cybersecurity leaning, but most of what I actually ship lately is Rust — a few COSMIC desktop applets because I got tired of missing GNOME extensions after jumping from Pop!_OS 22.04 to 24.04. Been distro-hopping for a while now (Mint, Fedora/Hyprland, Pop!_OS, Kali). Also doing TryHackMe rooms on the side and slowly working through CTFs.

**stack** `Rust` `Python` `JavaScript` `Bash` — `Nmap` `Wireshark` `Burp Suite` — `D-Bus` `libcosmic` — `Scikit-learn` `Pandas` `Next.js`

### stuff I've actually shipped

**[cosmic-internet-speed-monitor](https://github.com/AceMythos/cosmic-internet-speed-monitor)** — live up/down speeds in the panel, refreshed every second. Hourly sparkline for the day, monthly per-day bars you can click for the value, connection details (IPv4, IPv6, gateway, DNS) and Wi-Fi info (SSID, signal, link speed). Configurable refresh interval, bps/bytes units, interface, retention 7-90 days.

**[cosmic-connect](https://github.com/AceMythos/cosmic-connect)** — COSMIC applet wrapping KDE Connect over D-Bus (pairing, transfers, clipboard, SFTP). Also maintains a patched KDE Connect fork — added D-Bus signals for live transfer progress since upstream only tells you when a file's *done*, and fixed two daemon bugs while I was in there.

**[cosmic-power-monitor](https://github.com/AceMythos/cosmic-power-monitor)** — panel applet, shows real battery watts instead of just a percentage. Polls `/sys/class/power_supply` a few times a second. Shipped it to the COSMIC Store.

**[ClipManager](https://github.com/AceMythos/ClipManager)** — clipboard history for the COSMIC panel. Search, click to copy back, pin to the top, delete entries or clear all, private mode. Auto-clears after 48h, pinned entries kept.

---
reach me: [vishwanathsanapuro8@gmail.com](mailto:vishwanathsanapuro8@gmail.com)
