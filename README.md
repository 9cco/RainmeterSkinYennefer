# Yennefer: A Rainmeter suite

![Visitors](https://visitor-badge.glitch.me/badge?page_id=9cco.RinmeterSkinYennefer)
[![Say Thanks!](https://img.shields.io/badge/Say%20Thanks-!-1EAEDB.svg)](https://saythanks.io/to/9cco)

*Rainmeter* is a desktop application for *Windows* similar to *conky* on *Linux*. It allows the user to highly cutomize what is shown on the desktop by displaying small widget-like programs called *skins* that one can drag around. Each *skin* can contain a number of elements, but usually have a specific task like showing the current CPU usage. A collection of such *skins* are collected in what is known as a *suit*.

To use this suite, download and install Rainmeter from [https://www.rainmeter.net/](https://www.rainmeter.net/). Then go to the directory where Rainmeter stores the different installed skins, which is usually found at `C:\Users\YourName\Documents\Rainmeter\Skins`. Then download this repository into that directory by e.g. issuing the command
```
git clone https://github.com/9cco/RainmeterSkinYennefer.git
```
To load the skin, start Rainmeter, then left-click the Rainmeter icon in the taskbar, or, alternatively, right-click and choose '*Manage*' from the menue. Click '*Refresh all*' and
the folder '*Yennefer*' should appear in the '*Skins*' tab. Click the folder and navigate to the skin in the *Yennefer* suite that you want to load. Then click the '*Load*' button and the skin should start running on your desktop.

## Skin descriptions

#### Memory

Shows a graph of the Physical RAM usage as well as this information represented as a bar, a percentage and shows the total ram in GB.

#### Network

Displays local IP, gateway IP, and DNS server. Uses api.ipify.org to get the public IP and IPv6 addresses.

#### Network_Graph

Shows graphs of the total network usage for upload and download.

#### Time

A digital clock with fancy reflection that also prints the day and date above the numbers.

#### Vulnerabilities

Parses the CVE vulnerability API for the latest vulnerabilities that have a CVSS score that is sufficiently high. Displays these in a list with dates the vulnerabilities were published, their CVE IDs and the CVSS score. If you click on them you are taken to the NVD-website for the specified vulnerability.

#### Weather

Based on Sonder's weather system which parses the weather.com API. It displays forcasts for the next 3 days, the current moon phase, sun position, temperature, humidity and an icon signifying the current weather.

#### Wifi

A short line displaying current wifi connection strength and SSID. If you click on it, it shows more details.
