# Webots for NAO(virtual)

## Environmant

Naoqi

Choregraphe

Webots-8.6.2 or version before R2019

Webots download(old release):

https://github.com/cyberbotics/webots/releases?page=2

## Connection between Choregraphe and Webots

You can enter your login email randomly, but the password is "webots".

### After Connection

The robot view interface in Choregraphe is the virtual NAO in Webots, which is affected by gravity and can fall down. (The built-in virtual robot in Choregraphe is just a model, not affected by gravity and cannot fall down.)

Upon connection, the robot initially enters the StandZero state.

<img width="142" alt="image" src="https://user-images.githubusercontent.com/119626304/226732060-aa16fc5d-c8e5-4d08-a0d8-6f834c4a76ac.png">

It is recommended to connect a StandInit box before performing any actions. 

If the robot accidentally falls down, you can simply reload the world in Webots (the most convenient option).

<img width="202" alt="image" src="https://user-images.githubusercontent.com/119626304/226732571-d6d74d0e-b671-45c9-a72c-f33dd81fd76d.png">

## Error

Please turn off any VPN on your computer (or disable global mode) when connecting to the virtual robot.
