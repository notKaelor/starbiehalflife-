# starbiehalflife-
This is my project 4 half life! im building starbie with a bee hive theme! 🐝˚ ༘ ೀ⋆｡˚

So what is starbie? (u may ask urself)

Starbie is basically a desktop tamagotchi (digital pet) u can make by yourself inspired by starboy (yes u read that right, by yourself :3 )
<img width="1862" height="944" alt="image" src="https://github.com/user-attachments/assets/11d9cde2-d2ea-4a90-b885-2b557edba2f2" />
(image of the actual site of starboy)

I chose this project because i didnt have a clue of what to do cuz it was my first time dealing with hardware, kicad and arduino and this project seemed simple enough to start, i encourage everyone to give it a try!
I know my final results arent that pretty but i guess its cool 4 my first time messing around with this stuff.
Here u can see my first schematics using kicad yayy

<img width="1007" height="566" alt="image" src="https://github.com/user-attachments/assets/504eebcd-6c02-4e78-b450-ed01aa4ef10a" />

The star didnt look that good to me so i decided to replace it with some bee themed stuff, for the pcb i changed the shape to an hexagon

Here is an image of the pcb in the 3d viewer 

<img width="1683" height="914" alt="image" src="https://github.com/user-attachments/assets/014852d8-4b4a-42e7-95e2-0a1a6999dd8a" />

Then i changed the default desktop pet to one that suits the theme. Sooo heres a preview of the sprite ive made:

<img width="446" height="436" alt="image" src="https://github.com/user-attachments/assets/e29b7233-94c5-49f7-8ae6-97c87beb333a" />

How does this work?
Thats a great question i asked myself. 
Everything revolves around a xiao esp32c3, a sensor called MPU6050, a DHT11 sensor for temperature and humidity, also two buttons and a OLED display

The firmware is always in one of three views, the pet view, the menu or the stats view.
The stats change when u shake the board or when u pick an action.

What are the actions? 
welp the pet can nap play be fed or be petted. each action changes the stats and triggers an animation.
the program consists of a loop that repeats continuosly and the sprite of the pet is displayed by a couple of arrays. (mine has different arrays cuz i changed the default pet)

<img width="289" height="612" alt="image" src="https://github.com/user-attachments/assets/1d4f1802-2d31-4d88-b788-198b981b054d" />

I expect to make some changes later because im not satisfied with how the thing is right now but i had fun learning how to tinker with new software.
If possible i will try to make my own designs in the next weeks! One of my aspirations is to build my own keyboard

Also pardon my english as im not a native english speaker 


