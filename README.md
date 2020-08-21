# pyo-plug

Audio plugin using the python module pyo to create the dsp.

This plug-in allows the user to build his own signal processing chains with the python module **pyo**.
It presents a text editor to write code that can be compiled on the fly.

## Installation

Python 3.7 64-bit and pyo must be installed on the system before using the plugin.

[Python 3.7 download page](https://www.python.org/downloads/release/python-379/)

To install pyo on MacOS, open a Terminal and:

```
sudo python3 -m pip install pyo
```

To install pyo on Windows, open a Command Prompt and:
    
```
py -3.7 -m pip install pyo
```

Then, download the plugin from the [Release page](https://github.com/belangeo/pyo-plug/releases) 
and save it in the local VST folder of the system.

* If you use Reaper on MacOS, in order to be able to use space and return keys in the
code editor, you need to open the Fx chain window where is your plugin (right-click
on the plugin name in the mixer and choose "Show FX chain"), then right-click on the
plugin name and select "Send all keyboard input to plug-in".

## Donation

This project is developed by Olivier Bélanger on his free time to provide a 
fully integrated Python dsp module for sound exploration and music composition. 
If you feel this project is useful to you and want to support it and it's 
future development please consider donating money. I only ask for a small 
donation, but of course I appreciate any amount.

[![](https://www.paypal.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=9CA99DH6ES3HA)
