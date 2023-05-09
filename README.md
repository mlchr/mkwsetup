# mkw-setup

# TL;DR

Perfect setup:
- Console: Wii
- Controller: Gamecube Controller > Classic Controller via Raphnet adapter > Wiichuck/CC via 2.4g BT
- Monitor: CRT Monitor (or Viewsonic XG2431) > CRT TV (preferably with component) > High tier LCD monitors > LCD TVs
- Network: Ethernet via USB > Wireless

# Importance of low input lag

- ["While participants performed dragging and scribbling tasks, very low levels of latency could be discriminated, i.e., ~1 versus 2 milliseconds while dragging"](https://doi.org/10.1145/2556288.2557037).
- [Visual demonstration of 1 vs 10 milliseconds](https://youtu.be/vOvQCPLkPt4?t=80)
- ["The average difference in aiming task completion (the time it takes to acquire and shoot a target) between a 12ms and 20ms PCs was measured to be 182ms - that is about 22 times the system latency difference."](https://www.nvidia.com/en-us/geforce/news/reflex-low-latency-platform/#why-does-system-latency-matter)
- ["In all studies, the trend shows continued improvements all the way toward zero latency."](https://developer.nvidia.com/blog/aiming-faster-in-games-with-low-computer-system-latency/)
- ["In the first part, perceptual user experience under different jitter levels was examined using the ISO 4120:2004 triangle test protocol, and a jitter of over 0.3 ms could be perceived by sensitive subjects."](https://dl.acm.org/doi/10.1145/3472749.3474783)
- [Summary in form of an infographic](https://raw.githubusercontent.com/BoringBoredom/PC-Optimization-Hub/main/content/importance%20of%20low%20input%20lag/latency.png)

# Console

- [Wiis are superior to Wii U for latency. vWii emulation on the Wii U introduces roughly 1 frame of latency (16ms)](https://www.youtube.com/watch?v=Lb8zj5uKifk).
- [4:3 provides more vertical FOV, while 16:9 provides more horizontal FOV:](https://i.imgur.com/ctfwVZO.jpeg)
- [WiiDual](https://www.retrorgb.com/wiidual.html) is a physical mod that enables the Wii high quality 480p via HDMI (without introducing additional input latency). This will look better than vWii's upscaled 1080p and 480p via component or Wii2HDMI.
- [Wii HDMI Mod](https://arthrimus.com/product/wiihdmi-complete-install-service/)
- [Wii2HDMI Converters add negligible amounts of latency](https://twitter.com/Kadano/status/1026867743587483649)

# Controller

  - [Input lag sheet](https://docs.google.com/spreadsheets/d/1KlRObr3Be4zLch7Zyqg6qCJzGuhyGmXaOIUrpfncXIM/edit)

Wired controllers will always have less latency than wireless ones.

However, swapping controllers is not advisable as controller layout/familiarity is far more important than minor latency changes. However, with the adequate modding ability (technical knowledge and soldering), it's most likely possible to mod a wii to accept high-speed wireless. 

- It may be possible to mod a Wii and controller to use a different bluetooth controller.
- The Bluetooth the Wii uses has been shown to have roughly 16ms of latency in other consoles/applications.
- There is an adapter for the Classic Controller that allows it to connect to a GC port. This adapter has 4ms of latency, so it will cut the input latency by roughly 12ms.
- Phobb gamecube controllers and other similar will have more accurate and consistent input, as well as better longevity due to using hall-effect sensors rather than a normal stickbox. 
- You may find it useful to add notches into the control stick for better softdrifting ability



# Monitor
CRTs will always be the best displays for console games due to them having virtually 0 input lag and perfect motion clarity. There are *some* LCDs that may get within 1-2ms of a CRT's input lag, however, almost all of these have horrible response times, leading to non-static 3D objects (such as walls, items, etc.) to be blurry. 

Most CRT monitors have a 15khz minimum scan limit, which means 480i@60fps will not work. However, 480p@60fps is 31khz, and reaches the minimum scan limit. Because of this, any CRT monitor will provide lagless gameplay and you do not need to search for a high spec model that will cost you upwards of $500. 

The one downside to CRTs, especially consumer grade CRT TVs, is that they are often quite dark, making certain tracks, such as rBC, more difficult to drive on. 

The only LCD monitor worth purchasing is the Viewsonic XG2431 due to it's low processing latency of ~0.05ms, meaning it comes very close to a CRT in input lag. It will have worse motion clarity than a CRT, however, its response times are far superior to any other monitor at 60hz, so it will be less smeary/blurry than others. It is also one of the fastest 240hz monitors, so if you play competitive games other than Mario Kart Wii it is well worth the money. 

[List of LCD monitors input lag @ 60hz]









- ## Monitor Resources
  - ### Information
    - [Factors affecting PC Monitor responsiveness](https://pcmonitors.info/articles/factors-affecting-pc-monitor-responsiveness/)
    - [UFO Motion Test Database](https://docs.google.com/spreadsheets/d/180jSMtUKHsXVWBdG9LEYmTLWcBaTAEO9d7d4SUTgmTw/edit)
  - ### Reviews
    - [RTINGS](https://www.rtings.com/monitor/tools/table)
    - [TFT Central](https://www.tftcentral.co.uk/reviews_index.htm)
    - [Hardware Unboxed](https://www.youtube.com/playlist?list=PL7m5C6_P_lnXb9cHwdo0Ct1TTZ7KUwm3e)
    - [Monitors Unboxed](https://www.youtube.com/@monitorsunboxed/videos)
  - ### Tools
    - [Blur Busters' utilities](https://www.testufo.com/)
    - [ApertureGrille's utilities](https://www.aperturegrille.com/software/)
    - [Lagom monitor test](http://www.lagom.nl/lcd-test/all_tests.php)
    - [EIZO monitor test](https://www.eizo.be/monitor-test/)
    - [Custom Resolution Utility](https://www.monitortests.com/forum/Thread-Custom-Resolution-Utility-CRU)
    - [ControlMyMonitor](https://www.nirsoft.net/utils/control_my_monitor.html)
    - [Open Source Response Time Tool](https://www.osrtt.com/)
    - [piLagTester](https://alantechreview.blogspot.com/2020/08/pilagtester-pro-order-page.html) (input lag and response time tester)

