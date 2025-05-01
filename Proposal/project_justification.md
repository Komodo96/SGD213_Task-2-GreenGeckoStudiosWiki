# Justification
[//]: # (This section is an example of justifying your design and development decisions.)

## Overview

### Brief
[//]: # (What was the client's brief?)
The client is looking for an FPS template that can be used for their classes
* The player needs to be able to walk around and jump
* The game needs 2 weapons that the player can swap between 
* The player needs to be able to throw a damage dealing grenade
* The client needs a basic enemy AI that can walk around and look at the player

### Communication
* Do you have a name for the project or would you like our team to come up with a name?
> You are free to use a work-in-progress name for the project, as it would be changed later.

* What games other than Doom, Halo and Quake inspired you to make an FPS?
> You could look at later Doom-clones (Boltgun, Dusk, etc.) as well, though they all build on a similar template

* Do you have any specific requirements that need to be met in your game? E.g. Would you like the game to feel slow and tactical or fast paced and frantic?
> Most of the values that define the gameplay as you describe - movement speed, camera control, enemy spawns, etc. - should be available to be changed in editor, so you are free to pick a direction for the in-progress project

* What aesthetic does your game need?
> Your submission won't need any final assets, so even basic 2D/3D assets will do for the time being. Final assets and aesthetics are something I would implement later.

* What expectations do you have of our team and how we deliver our prototype to you?
> My expectations would be you continue to communicate on important updates and deliver it on time haha!

* Does your game require audio?
> A basic audio setup for the essential interactions would be nice, though it could be moved to a stretch goal if you require more time on other features.

* Does your game require assets to be outsourced or would you be happy for us to use grey boxes/placeholders?
> As in prior note, placeholder and greyboxes are sufficient.

* Does your game need UI elements? 
> Simple UI/HUD elements would be great: ammo and health counters, and a basic menu with some options like sound, though it could also be a stretch goal to be implemented if the time allows.

* Does your game have an established lore or universe that it takes place in?
> Similar to aesthetics, lore is something that would be added much later.

* Does your game need a menu?
> A simple Main Menu with a Start and Exit would be a minimum.

* Is there a specific thing you wish the enemy ai to do other than “look at the player”? For example, is the ai on a set path or are they moving freely? Does the enemy chase the player when they spot them?
> The enemies should walk around the level, though if you have the time to implement both free roam and patrol behaviours, that would be great.

* What types of weapons do the players have. Do they fire slowly, fire multiple projectiles, a big projectile, or fire quickly?
> Gun behaviour should be customizable from the Editor, so you feel free to experiment with the guns you give the player.

* What kind of grenade is it, what does it do? Does it damage nearby enemies, does it obscure the enemy's vision for a time, does it heal? How does it do this and when?
> A simple area of effect damaging grenade will do: much like the guns, most of its variables should be exposed in editor, so you can experiment with specific values (damage, if there is a delay after being thrown, etc.)

* What kind of movement are you looking for? Does it include running, jumping, crouching? Or is it simply just walking?
> The player should be able to walk around and jump.

* Do you want a visual for the weapons available on the character?
> As with other assets, feel free to use placeholder/greybox for the guns in the prototype.

* Do we need the player to start with both weapons or pick a new one up to be able to swap?
> The player should start with both weapons.

* Are there any pickups you would like implemented e.g. Ammo, Health, Grenades?
> All of the above would be great as pickups for the prototype! Should the time become an issue, please prioritize Health over Grenades and Ammo (as weapons should have an option of having unlimited ammo via an Editor) in that order.

* Does the player need to reload?
> The player should be able to reload, though no animation is required at this stage - a simple refresh of the current ammo is sufficient.

* Are the AI already in the level or do they spawn in?
> Whatever enemies are in present in the level should be there from the start as I do not need an enemy spawning system at the moment. At most, respawning enemies should be available as a simple debug feature (ie: Pressing O would respawn any enemies in the level) - something that won't make it to release build but can be useful for the designer to test.

---

## Project Understanding

### Requirements
[//]: # (What are the requirements of the finished project?)
* Needs the product in under 5 weeks
* The client has given our team freedom for how the game will feel. All values that define gameplay such as movement speed will be changeable by the client in the editor
* The game will have simple UI elements such as Health and Ammo count
* There will be a Main Menu with Start and Exit options
* The AI controlled enemies will walk around the level and look at the player. As a stretch goal they will use patrol and free roam behaviours
* How the guns behave will be customisable in the editor (Fire rate, projectile speed etc.)
* The player will be able to walk around and jump
* The player will be able to toss a Area of Effect grenade that deals damage
* A basic menu with options like sound can be added if time permits

### Expectations
[//]: # (What are the client's expectations?)
* The Project will be delivered on time
* Communicate with the client on important updates
* Our team will communicate with the client when issues are encountered
* The client will be added to the project to ensure quality transparent project management
* The game does not need any finalised assets, however greyboxes will be used as placeholders for characters and weapons
* If time permits the game will have basic audio components in place

### Assumptions
[//]: # (What are you assuming based on client responses)
* The UI design will be fairly basic with simple shapes being utilised
* Health will be indicated by a bar for the player and the ammo will be indicated by numbers on the HUD
* The enemy AI is already present in the level

---
## Risks

### Risks
[//]: # (What are the risks of this project)
* The potential risks that may occur for one or more of us are:
* Logistical issues like the power going out
* Team members getting sick or injured and being unable to work on the project
* Internet or connection issues
* Due to our teams relatively newer exeperience in coding there may be bugs present in the prototype

### Risk Management
[//]: # (How are you managing the mentioned risks)
* Using source control we will ensure our code is safe and usable at all times for all team members and other team members can help if needed 
* All coding will be thoroughly checked and insured to adhere to the correct coding standards
* Testing will be undertaken throughout prototype development

---

## Constraints

### Constraints
[//]: # (What are the constraints of this project)
* We have a limited amount of time to complete this project and deliver the prototype to the client
* We have a limited budget to work with as we are a small team which makes procuring outside resources an issue
* Our team is made up of new and upcoming coders so are technical skills are still developing
* The project is restricted to an FPS type
* The project is restricted to PC platforms 

---

## Justification
We decided to make a project that resembles early First Person Shooters, as per the clients request, and the name of the project serves as an homage to the title DOOM. We wanted to create a strong FPS
base template that could fit our clients needs, with modularity being a big focus across the board. This allows our client to customise their game's experience to their preference with an emphasis on building
a strong core for future development of their game. The game features many traditional systems that you would see in classic shooters like swapping weapons, movement. throwing grenades and AI enemies that can 
track the player. These will be built with component patterns and professional coding standards in mind. This allows for a highly customisable and enjoyable experience for our client. 
