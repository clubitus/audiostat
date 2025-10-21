# Audiostats

<p>A cool OBS music overlay !<br>
An OPEN-SOURCE overlay that shows the audio currently playing via winrt's API made with HTLM, JS and Python.<br>
It probably needs some improvements so feel free to contribute and help !
</p>

## About

<p>Audiostats works by having a websocket ran by a python script.<br>
The scripts comunicates with winrt's API and gets infos about the media currently playing.<br>
The HTML file then listens to that websockets and displays the title and artist of the media playing.<br>
Most of the HTML/JS were made using AI so it need lots of improvement that i'll add overtime if i find the time!</p>


## How to use

### Requirments

<p>Using ```python 3.9``` to support winrt.<br>
here's a list of all libraries used :

- winrt (```1.0.21033.1``` is the version I use)
- websockets (```11.0.3``` is the version I use)
- asyncio (came with my conda environement, don't think it needs/should be installed with pip)
- json (came with my conda environement, don't think it needs/should be installed with pip)
</p>

### make a .exe

If you want a ```.exe```  you can do this using pyInstaller :

1. run ```pip install pyinstaller``` 
2. run ```pyinstaller -F src/audiostat.py``` inside the main folder

( -F makes it so it compiles everything into a single file ! )

### use in obs-studio

1. Make a new Browser source
2. link the path to overlay.html : ```file:\\\Path\To\Your\File\overlay.html```
3. run ```audiostat.exe``` OR ```python audiostat.py``` 
4. the next media you play should send title \ artist into the overlay !

## More

Feel free to help improve the project !
If you have requests I might be able to help, keep in mind that I'm not good at this though !

---

*This project is licensed under the GPL-3.0 License - see the LICENSE file for details.*


*Last updated: 10/21/2025*

