# /interiortp (interiorname)

# Fivem InteriorTeleports
A simple script that makes a command so you can teleport between any interior that you cannot normally reach.
Here's a list of all the possible places you can teleport

doomsday doomsdaysub iaafacility
iaaserver hangar nightclub
unionvault morgue cocash
methlab modshop vehware
weedfarm bunker cocaine
houselow housemid clubhouse1-2
aptlow1-3 largegarage 1-4 largegarage1-4
office1-4 aptmid1-6 househi1-7

If the name includes something like 1-3 that means you can select a number between it and teleport to different variations of the interior. These variations are mainly just some changes or different locations when you look out to the window.

# REQUIREMENTS
You will need some sort of way to enable these interiors, a perfect resourse for this is bob74_ipl
https://github.com/Bob74/bob74_ipl

# How it works?
It's not that hard at all to understand, it takes the argument after the command and goes through an elseif. If the argument is seen as a valid name for an interior it'll simply teleport you to the coordinates. If the argument isn't valid, it'll send the person a list of valid interiors in the chat. This takes up 7 lines, so if you don't have default chat it may be cut off. If you want to change the teleport names, just go through the code and find the name and replace it, there's only one word you need to change (there cant be spaces). The code is modular, so if you just copy and paste in the right places, you'll have a new interior to teleport to, as long as you change the name and coordinates.
