---
layout: page
title: EAR Production Suite
subtitle: A collection of production tools for Audio Definition Model (ADM) compliant production, brought to you by EBU, BBC R&D and IRT.
---

<div markdown="1" class="text_section">
The EAR Production Suite (EPS) is a set of VST® plugins for digital audio workstations (DAWs) that enable sound engineers to produce and author content using the ADM format and to monitor it for any ITU-R BS.2051 loudspeaker configuration using the ITU ADM Renderer. Moreover, the EAR Production Suite enables professionals to import and export ADM files, compliant to the EBU ADM Production profile (EBU Tech 3392). The VST® plugins are currently optimized for the Reaper DAW, which features an extension interface that is used to import and export ADM files within a BW64 container. Apart from using it for productions, we envisage the EAR Production Suite as role model for further ADM implementations to harmonize ADM workflows and functionality.

The EAR Production Suite is a joint development of [BBC R&D](https://bbc.co.uk/rd) and [IRT](https://www.irt.de/en/home)
</div>

<div class="features">
  <div markdown="1" class="text_section feature">
  <img src="/images/codec-agnostic2.png">
  Codec-agnostic NGA productions
  </div>

  <div markdown="1" class="text_section feature">
  <img src="/images/speaker2.png">
  Loudspeaker setup independent mixing
  </div>

  <div markdown="1" class="text_section feature">
  <img src="/images/document.png">
  Native Audio Definition Model support
  </div>
</div>

<div style="clear: both;"></div>

<div markdown="1" class="text_section">
## Video Tutorial
[![Watch the video](https://irt-a.akamaihd.net/EAR-Production-Suite/Intro_image.png)](https://irt-a.akamaihd.net/EAR-Production-Suite/Intro_Beta-release.mp4)
</div>


<div markdown="1" class="text_section">
## Quickstart
### Import ADM Files
1. Select in the menu **File -> Create Project from ADM file -> Create from ADM using EAR**
2. Wait while all ADM elements are being created as tracks and automation curves along with metadata input plugins for each object or channel bed. There will be also tracks and plugins created for the Scene and the Monitoring.
3. Disable "Master send" for the **Monitoring** track routing and add your hardware output there
3. Enjoy :)

### Start with session template
1. Open template in REAPER
2. You will find a number of tracks with plugins for further usage
    - Two object tracks
    - One channel-based track
    - One EAR Scene bus
    - Two EAR Monitoring buses, one for Stereo monitoring and one for 5.1
3. The Scene Plugin has already two audio programmes, one called "English" and one "German"
4. All metadata connections between the plugins and I/O routings are set. You can start by importing your audio files into the tracks.
5. Switch between the different renderings by exclusive-soloing (CMD+Alt+Click (MacOS) / Ctrl+Alt+Click (Win)) the monitoring tracks.
</div>

<div markdown="1" class="text_section">
## Installation
The EPS is designed for REAPER 64-bit, on a 64-bit OS (macOS or Windows)

1. Install [REAPER](https://www.reaper.fm/download.php)
2. Copy / install the **VST plugins** into your common VST folder.
    - Windows: C:\Program Files\Common Files\VST3
    - macOS: ~/Library/Audio/Plug-Ins/VST3
3. Open REAPER and go to Options -> Preferences -> Plug-Ins -> VST and click Rescan
4. Copy / install REAPER ADM **Extension** into the REAPER plugins folder. Ensure you include the ADMPresets subdirectory.
    - Windows: C:\Program Files\REAPER (x64)\Plugins
    - macOS: ~/Library/Application Support/REAPER/UserPlugins
5. Restart REAPER
6. You should see a new menu option **File -> Create Project from ADM file** now. If you don't see this option and you are using Windows, it might be neccesary to download and install the [Visual C++ 2015 redistributable](https://support.microsoft.com/en-gb/help/2977003/the-latest-supported-visual-c-downloads) ("vc_redist.x64.exe") from Microsoft.

  <div class="button-grid">
    <button class="c-btn">Download macOS</button>
    <button class="c-btn">Download Windows</button>
  </div>
</div>

<div markdown="1" class="text_section">
## Contact
You can contact the developers of the EAR Production Suite via this mail: tbd@tbd.de
For feedback, feature request and bug reports, we would appreciate if you submit an [Issue](https://github.com/ebu/ear-production-suite/issues) on our Github page.
</div>
