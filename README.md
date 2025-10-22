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

1. Download latest release
   
   ![Download Screenshot](Readme-assets/Screenshot_9.png "Download")

2. Unzip file
   
   ![Unzip Screenshot](Readme-assets/Screenshot_1.png "Unzip")

3. Add new source in OBS
   
   ![Add Source Screenshot](Readme-assets/Screenshot_2.png "Add Source")

4. Select browser
   
   ![Select Browser Screenshot](Readme-assets/Screenshot_3.png "Select Browser")

5. Put file link and browser size (I recommend W:200 H:50 for browser size)
   
   ![Browser Settings Screenshot](Readme-assets/Screenshot_4.png "Browser Settings")

6. Run audiostat.exe
   
   ![Run Program Screenshot](Readme-assets/Screenshot_5.png "Run Program")

7. Windows Defender will probably flag it, here's the bypass:
   
   ![Defender Warning Screenshot](Readme-assets/Screenshot_6.png "Defender Warning")
   
   ![Defender Bypass Screenshot](Readme-assets/Screenshot_7.png "Defender Bypass")

8. This should be what you see when you run the program (different title and artist OBVIOUSLY). Now if you play a new media, the OBS source should display the name and the artist.
   
   ![Program Running Screenshot](Readme-assets/Screenshot_8.png "Program Running")
   
   

   
## Requirements to modify the program

The program runs with python 3.9.x it wont work with another version and the ".exe" is compiled with Pyinstaller

here's a list of all libraries used :

- winrt (```1.0.21033.1``` is the version I use)
- websockets (```11.0.3``` is the version I use)
- asyncio (came with my conda environement, don't think it needs/should be installed with pip)
- json (came with my conda environement, don't think it needs/should be installed with pip)

## More

Feel free to help improve the project !
If you have requests I might be able to help, keep in mind that I'm not good at this though !

---

*This project is licensed under the GPL-3.0 License - see the LICENSE file for details.*


*Last updated: 10/21/2025*


















