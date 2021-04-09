_WIP..._

# w10-change-audio-output-using-razer-synapse
How do you programatically use your keyboard to set audio output to a particular sound device? Here is _one_ workaround for that.

This workaround enables you to use keybinds to change the audio output of your machine. 
For example, I have my AirPods Pro connected via Bluetooth but at the same time I have wired headphones. 

# Requirements
* Windows 10 PC
* PowerShell
* [nircmd package](https://www.nirsoft.net/x64_download_package.html)
* Razer keyboard with [Razer Synapse](https://www.razer.com/synapse-3) software installed

# Hardware used
* [Razer BlackWidow Elite Mechanical Gaming Keyboard](https://www.amazon.com/gp/product/B07K1VXCDR/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)
* AirPods Pro (connected via Bluetooth)
* Regular wired earphones

# If you don't have Razer keyboard ...
* [Use AutoHotkey software](https://theitbros.com/hotkey-to-switch-audio-devices/) 

# Lessons learned
* Although not the easiest solution and if you don't want to install another software like AutoHotkey, you can definitely use this.
* I was against the idea of having two startup programs to do this task so I went with the nircmd package install.
* You can run executables/VBScript/batchfiles from Razer Synapse
