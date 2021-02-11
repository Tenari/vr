# Space Trading Design Doc

You are a budding pilot trying to make you way in the solar system by transporting cargo from point A to point B and not getting blown to pieces by pirates.

Combine Pardus with Space Engineers and put it in vr.

## Summary Information

- Setting: Solar System / Asteroid Belt
- Game Genre: VR MMO RPG with realtime space combat action
- POV: first, 3rd sometimes when you fly the ship

## Unique Selling Points

Autism/Complexity, Freedom of playstyle, MMO, Asteroid Belt Space setting (vs lightspeed star system jumping space settings), unique flight planning mechanic, unique 3d cargo-tetris loading mechanic, unique combination of automated + manual combat controls (can choose to pilot or man turrets, will auto pilot/auto aim otherwise), "realistic" economy allowing risk/reward balancing

## Game Loop

Take jobs, earn money, upgrade ship, take harder/bigger jobs, earn more money, buy better ship, repeat, eventually mog on all the noobs who have garbage ships

## Setting

When Humanity builds the technology for manned asteroid mining, a whole wild-west of human expansion will occur, because due to the vast distances, effectively governing all of humanity becomes techinically unfeasible. What remains is localized areas of control which are under various legitimate and semi-legitimate governmental organizations. Earth still has its local politics, but much of industry has been moved to space since crop growing is much cheaper on earth, and waste products of industry can just be launched into the sun relatively easily when your factory is in orbit.

Fortunately, the recent introduction of warp gates at key locations around the solar system has made trade between locations that have them much easier.

## Tutorial

You start out in the cockpit of a starter ship, with an ai teacher-bot in the seat next to you, while the ship floats in space. "Since today is your last day of flight school, we'll review everything necessary for you to safely pilot this ship." He teaches you how to change thrust, rotate, roll, set target in the nav-computer, manage fuel consumption, use targeting computer, manually control turrets, launch dummy missile, change shield power distribution, and dock with a space station. 

## First Job

After you dock at the space station, the tutorial is over and you have a pilots license. You start out in rinky dink starter space ship (the Pardus equivalent of the Sabre) and can now do whatever you like, as long as it makes enough money to keep fuel in your ship. There are two main ways to play the game: trader and combatant.

### Trading

There are thre main types of trading run:

- Contract cargo
- Spec cargo
- Personnell transport

Contract cargo is when someone at point A pays you to transport cargo for them to point B. They will require a bond of a certain credit amount to insure them against lost cargo, which will be returned upon receipt of the cargo.

Spec cargo is when you buy some materials at point A and transport it to point B where you "speculate" that the price will be higher and you can make a profit.

Personnel transport is when a rich guy hires you to move him from point A to point B as a passenger. You must have a passenger berth to take these jobs.

### Combat

There are a few ways to make money off of combat:

- escort mission
- patrol mission
- piracy
- bounty hunting

Escort missions are where you escort a convoy/ship that is usually some sort of cargo hauler that would be defenseless on its own from point A to point B. If no pirates attack, you might not have to do anything other than fly with them, but often pirate drones will at least poke at your defenses to see if its worth a full attack.

Patrol missions are where a station or business hires you to patrol an area and destroy any unauthorized ships or drones you find.

Piracy is where you attack traders and steal their stuff to resell yourself for 100% profit.

Bounty hunting is where you blow up pirates in exchange for money.


## Mechanics

The main game mechanics that have to work to make the game work are the ship controls and the economy. Ship controls make combat fun/possible as well as facilitating transportation of goods. The economy makes transportation of goods profitable and interesting. If the game just paid you a flat rate for every package you transport, trading would be boring, but if there is a semi-fluid economy where there are real risk/reward factors at play, then trading becomes much more engaging.

### Ship controls

Typically, when travelling from point A to point B, you plan your route/burn plan first, and then tell the ship's computer to execute it. However, manual override is always possible, especially during emergencies.

#### route planning

When you are creating a burn plan you put in point A and point B on a menu, and then a zoomed out map of space appears, with A and B highlighted. You then specify the path to take, and how long to accelerate, which makes the computer estimate how much fuel you're using up. you can adjust things until you're satisfied and then tell the ship to do it.

#### manual control

You can look through the cockpit window or have your AI show you a 3rd person view.

you have joysticks for changing thrust, rotating, and rolling. You can also set specific values in the computer these things.

set target in the nav-computer, manage fuel consumption, use targeting computer, manually control turrets, launch dummy missile, change shield power distribution, and dock with a space station

## Idea grid questions

### Worldbuilding and Style

What central mood or feeling are you trying to evoke through the VR environment?

space exploration/constrained freedom (you are free to do what you please, but you are bounded by what you can afford/plan, etc)

Will the experience be accessible to all users?

meh. not all, but it should be playable from a spinny chair

What impact could the worldbuilding and style have on a range of different users?

## Scope

The game is open ended/ "infinite" play time, but realistically, you should be able to get to end-game ship in about 50 hours

There should be a number of space stations/planetary bases proportional to the userbase, with a minimum of 3. Probably want 1 base per 50 players but im just spitballing

An average job should take about 45 min to an hour to complete (including planning/prep time)

objective is to fly a cool big ship

you do have a semi-customizable character with different rpg stats. I think it would be funny to be full-on racist and allow people to choose their human race and give buffs corresponding to irl stereotypes (no penalties obviously) but I am aware that would not be well recieved by the modern audience. But the main thing you upgrade/customize is your ship

## Art Style

I'm envisioning space engineers with just a little less "blockyness" and smoother textures.

## Player Profiles Stories

There are two main variants of playstyle: agressive and passive, with of course room to find your place on the spectrum

For people who like the autism/planning side of things (passive) they can go full trader where they either play the package delivery game for lower risk and lower return or they play the spec-delivery game for higher risk higher return

For people who like the action side of things (agressive) they can either go hard mode and be a full on pirate and be hated by everyone else, or they can play sligtly more defensively and do patrol/escort missions

## Milestone Schedule

- cube-based asteroid and cube-based space ship that can be piloted around the asteroid from the first person cockpit or the 3rd person "ai" view
- turret + turrent control mode, blow-uppable cubes.
- missiles
- well-modeled Sabre-ship equivalent that you can walk around in, or sit in the pilots chair to pilot. Can visit empty cargo bay, go through internal door, etc.
- a space station you can land at
