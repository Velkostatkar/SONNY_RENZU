# SONNY_RENZU
Completed QBCore version of Renzu_hud, renzu_engine and renzu_turbo in one pack.
ALL GLORY TO RENZU: https://github.com/renzuzu


# HUD
- Fivem HUD - UI Framework include Street HUD, Status Hud, Speedometer Hud, Weapon Hud, Body Hud and many more.
- Design to work with Qbcore framework.


# Features
- Advanced Player Status System
- Draggable UI Status,Car HUD (position will restore upon reconnect)
- Multiple Status UI version (icons,circle progressbars, flat progressbars)
- Multi CarHUD Version (Simple, Minimal, Modernized)
- Weapon HUD
- Street HUD
- Engine Overheat System   --default is OFF
- Engine Swap System (Performance and sound)
- Car Status
- Car Control
- Vehicle Keyless System
- Body Status System
- WheelStancer
- AirSuspension
- Neon Color Control
- Neon Color Multiple Effects
- Seatbelt System
- Drive Mode - Sports or Eco or Normal, Drift Mode
- Built in Car GPS
- Mileage System
- Nitro System
- Advanced Tire System with items
- Advanced Turbo System with items
- Water and Engine Oil System (WIP)
- Manual Transmission
- Waypoint Large Marker
- Distance to Waypoint Calculation to UI
- Clock
- Gear
- RPM Text and Radial Bar
- Speedometer Text and Radialbar
- Fuel tank meter
- Vehicle Health Meter

-much more not included yet..

#Maximum Possible Optimisation
Client Side Lua and Javascript Side


# Main UI preview
- Settings
```
- F9 (default) and command /hud
```
![image](https://user-images.githubusercontent.com/70021784/155804557-eb4f42ca-5fa2-4ff7-a039-bfa534ddfb6a.png)

3 versions of car hud

![image](https://user-images.githubusercontent.com/70021784/155804435-4ed0297c-9dd6-4ed9-9722-1dd7b50619d4.png)





#BodyStatus HUD

By pressing HOME button you can see whats happen to you

![image](https://user-images.githubusercontent.com/70021784/155806459-a9112159-15e7-4d25-9cea-761e45ef0403.png)

and if you meet a doctor he can
/checkbody to pop your status on his screen.
Then he can heal by items

![image](https://user-images.githubusercontent.com/70021784/155806965-50e77edd-8fb2-43fd-9ae0-6e5bdc77847d.png)









#Turbo system


Change Vehicle Turbo system

![image](https://user-images.githubusercontent.com/70021784/155804495-38f8d0bc-5e06-4658-b2cf-c13aac3c4d08.png)
![image](https://user-images.githubusercontent.com/70021784/155805198-600404bd-41bf-4669-b0f8-f021e5adda6c.png)




#Feat


Custom BOV Sounds for each Turbo variants

Custom Power for ea Turbo Variants

Power Multiplication Sync with renzu_nitro

Item Supported

Job Supported




#Usage:

/giveitem turbostreet 1 --sound effect and boost of turbo
/giveitem turbo_street 1 --instal a prop and boost of the turbo on car, synced

/giveitem turbosports 1 --sound effect and boost of turbo
/giveitem turbo_sports 1 --instal a prop and boost of the turbo on car, synced

/giveitem turboracing 1 --sound effect and boost of turbo
/giveitem turbo_racing 1 --instal a prop and boost of the turbo on car, synced

default config only mechanic






#Nitro system

/giveitem ID nitro 1
then in car pres DELETE to ON/OFF the nitro
activate nitro with left shift
![image](https://user-images.githubusercontent.com/70021784/155804903-96b5543d-ecd6-4dce-9b1b-e81c50a9772a.png)
![image](https://user-images.githubusercontent.com/70021784/155805019-2c62c9d7-28b2-483c-a783-af0beec78a35.png)







#Engine:
Change Vehicle Engine Sound and Sync to all server One Sync/One Sync Infinity (included carsound pack from gta5mods)


Custom Engine
Custom Specs
Custom Sounds
Fully Server sync using Onesync state bags

Use
as a mechanic you next to car write

/installengine zentorno
/installengine supra2jzgtett
and with arrow down place engine into car

![image](https://user-images.githubusercontent.com/70021784/155805567-68046462-c0a0-46d0-a997-25e235673c66.png)


or
just changesound of your car
/changesound elegy
/changesound toysupmk4




#TIRE SYSTEM

Usage
/repairtire  --for mechanics becouse your tires isnt immortal so you must go to mechanic for repairs
-- usable tire items with different handlings

![image](https://user-images.githubusercontent.com/70021784/155805883-f6cd4ce5-4e48-4ae4-9ea6-4d69ca588824.png)
![image](https://user-images.githubusercontent.com/70021784/155806008-931c6c79-3053-4215-8139-b6199b39aa68.png)






#Car Status

by pressing a key U, pop the status of your car

![image](https://user-images.githubusercontent.com/70021784/155807542-ae7d3bce-7ba5-4913-a06e-3c4618f07555.png)

there you can see the condition of your car whats instales and oil and tire usage so mechanic chan
/repairtire
or 
/changeoil

![image](https://user-images.githubusercontent.com/70021784/155807789-30e887ad-ed23-401b-bfc4-920f4e1a4e72.png)


#DRIVE MODE
by pressing right shift you changing driving modes
ECO, NORMAL, SPORT, DRIFT 



#CAR CONTROL
by pressing NumLock you pop a car control menu
that mean you can by defauld DELETE VSTANCER from your resources

![image](https://user-images.githubusercontent.com/70021784/155808202-2486fa63-52bd-423b-b2e4-acb30d6e5d34.png)
![image](https://user-images.githubusercontent.com/70021784/155808311-c1f836e5-f6ab-47cb-8d6e-2a7c3861ae3f.png)



# Dependency
- qb-core
- renzu_hud  --included
- renzu_engine --included
- renzu_turbo --included

# NO MORE NEEDED TO HAVE
- vstancer  --can be removed from your files becouse hud have self stancer modes

# Installation
- Download [SONNY_RENZU]
- Extract
- rename to [SONNY_RENZU]
- ensure [SONNY_RENZU] --after [qb]

#SQL
open folder [SONNY_RENZU]
and instal: hud_turbo_engine_bodystatus.sql


# TODOS
- Settings UI ✔️
- Fix Css
- Translation
- Other Framework integration
- More Optimisation
- Bug Fixing if any
