<div align="center">
  <img src="./assets/hero_banner.svg" width="100%" alt="Martyn McIntee - Ubuntu desktop tools, Linux hardware tinkering, and local LLMs on 24GB VRAM" />
</div>

<br/>

Hi, I'm Martyn. I moved my main PC from Windows to Ubuntu 24.04 and got fed up not having proper Linux apps for bits of hardware sitting on my desk - mainly my Corsair iCUE LINK watercooler screen, case fans, and Elgato Facecam 4K. Most of what's here started out as me writing the missing GTK4/Qt desktop tools and small `systemd` daemons so my own setup works the way I want without booting back into Windows.

The rest is local AI tooling for my 24GB RTX 3090 (keeping `llama.cpp`, `ComfyUI`, and CPU-side embeddings from fighting over the same 24 gigs of VRAM), an offline Linux replacement for the LoseIt! calorie tracker with proper UK stones-and-pounds support, and a 2026 tribute to Activision's 1985 Commodore 64 *Little Computer People* living inside my circular cooler LCD.

### Projects

<p align="center">
  <a href="https://github.com/martynmcintee-tech/corsair-titan-lcd-linux"><img src="./assets/card_corsair_titan_lcd.svg" width="49%" alt="corsair-titan-lcd-linux - C64 Little Computer People tribute and 13 circular AIO faces for Linux" /></a>&nbsp;&nbsp;<a href="https://github.com/martynmcintee-tech/elgato-camera-hub-linux"><img src="./assets/card_elgato_camera_hub.svg" width="49%" alt="elgato-camera-hub-linux - GTK4 + V4L2 webcam app for Elgato Facecam 4K" /></a>
</p>
<p align="center">
  <a href="https://github.com/martynmcintee-tech/openlinkhub-gtk-control-center"><img src="./assets/card_openlinkhub_gtk.svg" width="49%" alt="openlinkhub-gtk-control-center - GTK4 fan, gamma-2.4 RGB, and tray app for OpenLinkHub" /></a>&nbsp;&nbsp;<a href="https://github.com/martynmcintee-tech/linux-ai-vram-guard"><img src="./assets/card_ai_vram_guard.svg" width="49%" alt="linux-ai-vram-guard - Linux CPU governor and idle CUDA VRAM daemon" /></a>
</p>
<p align="center">
  <a href="https://github.com/martynmcintee-tech/loseit-local"><img src="./assets/card_loseit_local.svg" width="49%" alt="loseit-local - Offline PySide6 calorie and weight tracker for Linux" /></a>&nbsp;&nbsp;<a href="https://github.com/martynmcintee-tech/synapse-mind"><img src="./assets/card_synapse_mind.svg" width="49%" alt="synapse-mind - Local multi-model router and web UI for a 24GB GPU" /></a>
</p>

<details>
  <summary><strong>Little Computer Person running on my Corsair TITAN 360 RX cooler (live camera clip + 480x480 feed)</strong></summary>
  <br/>
  <div align="center">
    <a href="https://github.com/martynmcintee-tech/corsair-titan-lcd-linux"><img src="https://raw.githubusercontent.com/martynmcintee-tech/corsair-titan-lcd-linux/main/assets/titan_lcd_real_readme.gif" width="360" alt="Live Corsair TITAN 360 RX LCD footage on Ubuntu" /></a>&nbsp;&nbsp;<a href="https://github.com/martynmcintee-tech/corsair-titan-lcd-linux"><img src="https://raw.githubusercontent.com/martynmcintee-tech/corsair-titan-lcd-linux/main/assets/lcp_2026_showcase.gif" width="360" alt="Animated 6-scene LCP 2026 pixel feed" /></a>
    <p><em>Grew up wasting hours on Activision's 1985 C64 Little Computer People as a kid and wanted the little fella living inside my circular watercooler screen. Drawn in Pepto's 16-colour VIC-II palette and pushed to OpenLinkHub over persistent HTTP/1.1 keep-alive.</em></p>
  </div>
</details>

<br/>

### Desk Setup & Usual Tools

<div align="center">
  <img src="./assets/architecture_strip.svg" width="100%" alt="Ubuntu desktop and local AI stack" />
</div>

<br/>

*Note: I build these for my own Ubuntu desktop with AI coding tools helping out on UI boilerplate, math, and protocol plumbing, and everything is tested on the actual hardware sitting on my desk. All public repos here are MIT licensed - if you've got the same kit on Linux, help yourself.*
