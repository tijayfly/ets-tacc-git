Welcome to the Github repo for ETS Freeway Assist. This will always contain the latest version. The initial commit was v1.5.

Feel free to modify, make pull requests, fork or publish derivative works, but please always credit this repo in any such products.

ANY PULL REQUESTS CONTAINING MODELS WILL BE REJECTED - THEY ARE DOWNLOADED AT RUNTIME, SO PLEASE ADD THEM TO GITIGNORE.

INSTALL:
- Follow https://www.youtube.com/watch?v=nPgPhqq4OTo to install static version 1.4, learn how to set up ETS and run the script
- Download or clone this repo into your ets-tacc folder and overwrite when prompted
- Revise line 102 to point at your Tensorflow folder in your user directory, just as you did during install
- Run tacc.py for cars and tacc-trucks.py for trucks

USAGE IN-GAME:
- CARS ONLY: To activate/deactivate TACC with Autosteer ("Autopilot"), press C
- CARS ONLY: To change lane while Autosteer is active, press Z or X on a straight freeway
- CARS & TRUCKS: To activate/deactivate TACC without Autosteer, press N

RECOMMENDED VEHICLES:
- CARS: Tesla Cybertruck, Tesla Model S, Ford Transit
- TRUCKS: DAF

FILES:
- directkeys.py: Exports keycodes for use in tacc.py
- grabscreen.py: Library 
- tacc.py: Main script for use with cars (full "Autopilot")
- tacc-trucks.py: Main script for use with trucks (TACC only)
- PYTHONPATH.txt: Adds Tensorflow to PATH, must be run before main script
- steering.jpg: Recommended steering settings in ETS
- .wav files: Sounds used in Freeway Assist

THIS PROJECT USES SOME COMPONENTS FROM THESE EXISTING PRODUCTS:
- https://pythonprogramming.net/detecting-distances-self-driving-car/
- https://github.com/JackPaul3413/self-driving-car-using-opencv-test-with-forza-horizon/tree/master
