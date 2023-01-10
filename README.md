# squadmc-maps
This forked repo is used for holding the [mapdata](http://ssrgaming.club:32101/) for this [copy](http://squadmc.ssrgaming.club/) of [SquadMC](https://github.com/Endebert/squadmc).

# Usage

SquadMC works with external maps hosted on maps.squadmc.ende.pro. However, if you wish to host and serve them locally, follow these steps:

 0. `npm install -g yarn`
 1. `yarn install`
 2. `yarn run mapdata`
 3. `yarn run serve`
 4. adapt the baseUrl variable in the squadmc repository (`squadmc/src/App.vue`), to whatever `http-server` tells you
 
 # Adding new maps
 
 To learn how to add new maps to this repository yourself, please check out this wiki page: https://github.com/Endebert/squadmc-maps/wiki/How-to-add-new-maps-to-SquadMC
 
 I'm looking forward to your contributions!
