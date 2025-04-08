# Setup
Both Normal Load and High Load were tested twice on the poodle map: https://beatsaver.com/maps/416ac. 
Chose a poodle map as the underswing affects the entire poodle or most of it, making it highly noticeable.

## Normal Load 
The Normal Load test was conducted with the game in focus, while simultaneously streaming on Discord, as this is the typical setup I use when playing.

## High Load 
For the High Load test, I ran FurMark with a limited FPS to make Beat Saber still somewhat playable, along with a Python CPU benchmark (from this GitHub repository: https://github.com/alexdedyura/cpu-benchmark). I modified the benchmark to only run the Multithreaded portion.
CPU usage: 100%
GPU usage: 90%
The game was also unfocused to further increase the chances of stutters.

# First Glance
1.29.1 did not have any fully underswung poodles.

1.39.1 on both SteamVR versions had some clear underswing on entire poodles. 

The new SteamVR 2.10.2 is a **LOT** better than SteamVR 2.9.6 while under high load.
The new SteamVR 2.10.2 seems to be performing on par with SteamVR 2.9.6 while under normal load, both having underswing issues.
