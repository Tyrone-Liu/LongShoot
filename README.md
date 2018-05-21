# Long Shoot

**Long Shoot** is an ***experimental*** android camera app using camera2 API.  
The purpose is shooting **long exposure photo** and **stacking photos** with RAW output and full control of shutter parameters.  


## Progress
One thing I need to clarify is that before a certain state of development, this app is definitely **unuseable**.  Most of the experimental work will be done in my other repo [ExperimentalApp](https://github.com/Tyrone-Liu/ExperimentalApp.git), because I do not want this repo to become massive while I am learning Android programming and experimenting camera2 API features.  


## Features & To-Do

+ Full control of shutter parameters
    * Focus
        - [ ] Auto focus
        - [ ] Manual focus
    * [ ] Exposure time (Shutter speed)
    * [ ] ISO
    * Exposure bracketing (BRK)
        - [ ] Numbers of shot in BRK
        - [ ] Exposure distance between each shot in BRK
    * [ ] GPS record for shots
    * [ ] White balance (When you have RAW output, white balance is not that demanded)
    * [ ] Flash control (Flash lights on phones may not be a good choice for great photos)

+ Photo output
    * [ ] Choice between RAW (DNG) / PNG / JPEG output or any combinations of them
    * [ ] Write correct metadata into files or embed in shot
    * [ ] Custom output file name with patterns

+ Burst (for stacking or time-lapse)
    * Control method: Switch
        - [ ] Switch / button to start / stop burst (no need to press shutter button many times)
        - [ ] Configurable time interval between each shot / shot group
        - [ ] Configurable shot numbers for each shot group
    * Control method: Button
        - [ ] A button to start a burst with a number of shots
        - [ ] Configurable shot / shot group numbers
        - [ ] Same function as the last two in 'Control method: Switch'
    * [ ] Work with BRK for each shot / each shot in each shot group
    * [ ] Name photos like single shots, but add numbers to identify burst groups
