### Animepahe Auto Download Script

> This script is not a (batch downloader), it's automation for animepahe.(ru|org|com) written in javascript. 
compatible with any browser supported by 'Tampermonkey' across devices (Google Chrome · Mozilla Firefox · Safari · Brave etc). 
For mobile, use the 'Kiwi Browser - Playstore' or any browser that supports chrome 'Extensions' or 'Tampermonkey'.

### Prerequisites
- 'Google Chrome Browser' or your 'Browser' of choice that supports 'Tampermonkey' Extension.
- Google Chrome Javascript Extension : [Tampermonkey](https://chrome.google.com/webstore/detail/dhdgffkkebhmkfjojejmpbldmpobfkfo)


```
Usage:

- [menu]                   located at the top webpage of 'animepahe' paths supported /play/ /anime/ /page?=xxx.
- [enable script]          enable/disable script 'animepahe' site only.
- [resolution entry]       1 · 360p, 2 · 720p, 3 · 1080p. min value (1) max value (15). absolute by entry order.
- [test entry]             test 'resolution entry' and will highlight the value in entry.
- [subtitle·english]         switch to subtitle english · dubbed english only. 
- [resolution checker]     lock to selected 'resolution entry' 1 to 3 only.
- [all links]              unlock all links (by absolute order of resolution entry value).

Info:
open anime links in animepahe.(ru|org|com)/anime/ or /play/ using mouse scroll click/normal click to open multiple links.

```
#### Default Settings
![image](https://github.com/Ysilven/animepahe-script/assets/88947398/734f2aa3-56ef-4605-9bdb-b925bc904fe4)

```
Features:

- [auto resolution]        fallback feature for anime with limited resolution selections.
- [bypass]                 bypass waiting time.
- [page expire]            fix 'page expire' token issue.
- [reload 5 seconds]       will reload 'resolution checker' (enabled), if entry resolution is not 'yet' available.

written in javascript for tampermonkey extension. 
```

The settings will be saved locally and sync across all tabs. Feel free to modify the source code and submit bug/reports.
