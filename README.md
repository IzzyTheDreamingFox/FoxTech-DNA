> [!IMPORTANT]
> DNA is currently in a pre-release state. Many additional features are yet to be implemented in this alpha version and, although tested, bugs will still be present. If you encounter any problems, or have ideas for additional features, please let me know! <br>
> <br>
> DNA has been made with vanilla NMS in mind. Mods that alter the game, such as change the maximum amount of products/substances per slot, can cause some issues with the inventory system. Always use the back up system before using the app.

<h1 align="center">  
    <img width="558px" height="500px" src="images/intro-logo.png" alt="Logo" > 
    <div align="center"> Is it in your DNA to collect ships? </div>
</h1>

# FoxTech-DNA
<details open="open">
<summary>Table of Contents</summary>

- [Introduction](#introduction) 
- [Quick Feature Overview](#quick-feature-overview)
- [Planned Feature Overview](#planned-feature-overview) 
- [More Information](#more-information) 
- [Screenshots](#screenshots) 
- [Getting started](#getting-started)
  - [Compatibility](#compatibility)
  - [Requirement](#requirement)
  - [Usage](#usage)
- [Licence](#licence)
- [Contact \& Support](#contact--support)
- [Author](#author)
- [Credits](#credits)  

</details>  
 
# Introduction
${\LARGE\textsf{\color{#f11616}DNA}}$ 
${\LARGE\textsf{\color{#e6edf3}(}}$ 
${\LARGE\textsf{\color{#f11616}D}\normalsize\textsf{\color{#e6edf3}reamingFox’s}}$ 
${\LARGE\textsf{\color{#f11616}N}\normalsize\textsf{\color{#e6edf3}o Man’s Sky}}$ 
${\LARGE\textsf{\color{#f11616}A}\normalsize\textsf{\color{#e6edf3}pplication}}$ 
${\LARGE\textsf{\color{#e6edf3})}}$ 
is a tool for the game **No Man’s Sky** with which you can easily catalogue ships, multitools, freighters, frigates and pets with the option to save them on your system and transfer them across your save files. As a reward for your cataloguing efforts you’ll be able to interact with a trading card generated with the information you provided.<br>
It also comes with a full inventory system to manage, charge and quick-sort all your items along with the option to transfer those across saves. <br>
But that’s not all. The feature list keeps growing as the development continues.


<details  >
<summary> ${\textsf{\color{#f11616}Why does the DNA look the way that it does?}}$  </summary>
In an attempt to make the DNA feel more like an extension to the game itself then a separate program, I focused on getting the aesthetic of the application as close as possible to the actual game. With some tweaks and new things to allow the application to do what it has to do.<br>
Since every major race in the game apparently has a tablet, I’d like to imagine that this is one of the apps they have running on it. Something that connects them to various mega-corporations that offer their services for a price. Something to check their bank account with, check the stock market (which is in the game but players can’t interact with it), etc.

</details> 


<details  >
<summary> ${\textsf{\color{#f11616}Why did you make this project?}}$  </summary>

I like No Man’s Sky but once I reached the endgame the game became stale and some issues started to annoy me. <br>
Since I’m a chaotic person, my inventories become a mess and sorting them by hand is tedious. <br>
It also pained me to scrap good looking and upgraded ships just because I wanted a new one but ran out of slots. <br>
The same happened with multitools, pets, etc… I also wanted to mix it up by owning multiple freighters which the game simply doesn’t allow. Even frigates have a cap to them. With nothing to spend the endless money on the game grinded to a halt. <br>
At this point I was getting familiar with an editor by [goatfungus](https://github.com/goatfungus/NMSSaveEditor) and later the [NomNom](https://github.com/zencq/NomNom/tree/master) editor which I used to decrease my currencies and export my ships/tools as JSONs.<br>
While this worked, the temptation of the ability to cheat in anything I wanted was a bit strong.<br>

Then the idea of DNA was born. 
<br>
The idea of an easy-to-use application, that looks visually pleasing, filled with features for me to extend the lifespan of my enjoyment of the game.<br>
An application where I could, without a hassle, catalogue and save anything I own to free up slots in the game. Something that allowed me to sort my inventories automatically and transfer items/currency from one save to another.<br>
And allowed me to make certain ‘cheaty’ changes for a set cost, replacing the feeling of having cheated with the feeling of having worked for it.<br> 
</details> 

<details  >
<summary> ${\textsf{\color{#f11616}Why did you release this project?}}$  </summary>
I’ve been working on my own on this for a long while now and it has come to the point where I think others could get some use out of it as well. I implemented all the features I personally use and have some issues as to how to take the project further.<br>
I’m hoping that with user feedback I can start implementing features that, while I have no use for them, others might. And, together with others, we could take DNA and refine it into something more.
</details> 

   
 
# Quick Feature Overview
- **Platform selection**
  - Manage saves across platforms
- **Backups**
  - Automatic backups every time a save-edit is made.
  - Recover saves by restoring a previous backup.
- **Ship management**
  - Catalogue the ships you own.
    - Add all kinds of information such as portal location, system information, etc… 
  - Transfer ships to the database for later use, freeing up slots for you to use.
    - All information is saved. Such as inventory and technologies in the case of ships
  - Transfer ships between saves and different platforms.
  - View your collection in the form of interactive trading cards.
    - Customise your card with the in-app options
    - Export your trading card as an image. (It wouldn’t be a trading card if you couldn’t.)
- **Pet / Freighter / Frigate / Multitool management**
  - You can do the same things as with managing the ships!
  - Catalogue everything
  - Transfer everything to the database or other saves.
  - View everything as cards.
- **Inventory management**
  - Drag and drop items and tech from one inventory to another, similar to the game.
  - An extra account inventory is added to transfer items between saves.
  - Unlock/lock slots.
  - Supercharge/(subcharge?) your tech slots.
  - Quick sort your inventory
	  - Items will be sorted to inventories that already have at least one of that item.
	  - Configure the slots you don’t want to sort.
  - Quick charge all your technologies.
- **Base management**
	- Change the order in which your bases show up in the teleporter screen
	- View the amount of objects you have placed
	  - Across all bases and for each base individually
	  - View a list of all the objects within a base.
- **Settlement management**
	- General overview of your entire settlement.
	- Change the next judgement of a settlement.
	- Change the production of a settlement.
	- Change the features of a settlement.
- **Recipe finder**
  - Look up any recipe from the game.
	  - Favourite the ones you need for easy access.
- **Game launcher**
  - Set the path to the game and launch the game directly from DNA.
- **Bank/Stocks**
  - Transfer your currencies to a bank and use them for various services.
  - Invest on the stock market for big ~~losses~~ wins.
- **Extras**
  - Unlock new card-styles with salvage data.
  - Animated ‘advertisements’ based on in-game posters.
  - Since DNA is a save–editor at its core you’ll be able to check the developer mode option in the settings which will allow you to add/change items in your inventories.
  - The entire app is contained on your system and available without an internet connection.

 
# Planned Feature Overview
Here’s a list of some of the features I noted down. These might change depending on the feedback I receive.
- **Service costs for storing properties in the hangars.**
  - These will be deducted weekly from you the in-app bank-account and adjusted based on your standing with various guilds. <br>
   (Possible to switch this off in the settings.)
- **Item mall featuring companies selling in-game items at various prices or in exchange for other items.**
  - The option to buy locked expedition items with quicksilver
- **Reward system for playing the game**
	- Awards will include currencies, items and new card-styles.
- **Further expansion of the bank to include things such as loans.**
- **Option to create your own card textures and use them in DNA** (if there are enough requests for this)
- **Reward system for building bases.**
- **Fight for better performance**
 
# More information.
Check out the [wiki](https://github.com/IzzyTheDreamingFox/FoxTech-DNA/wiki#foxtech-dna) for more information about some of the features

# Screenshots 
  <img src="images/dashboard.PNG" alt="dashboard.PNG"  >  
  <img src="images/animation-dashboard.gif" alt="animation-dashboard.gif" >   
  <img src="images/inventories.PNG" alt="inventories.PNG"  >  
  <img src="images/animation-card.gif" alt="animation-card.guf" >  
  <img src="images/weapons.PNG" alt="weapons.PNG"  >  
  <img src="images/freighters.PNG" alt="freighters.PNG"  >  
  <img src="images/ship-detail1.PNG" alt="ship-detail1.PNG"  >  
  <img src="images/ship-detail2.PNG" alt="ship-detail2.PNG" >  
  <img src="images/ship-detail3.PNG" alt="ship-detail3.PNG"  >  
  <img src="images/properties.PNG" alt="properties.PNG"  >  
  <img src="images/recipes.PNG" alt="recipes.PNG" >  
  <img src="images/bank.PNG" alt="bank.PNG"  >  
  <img src="images/stocks.PNG" alt="stocks.PNG"  >  
  <img src="images/store.PNG" alt="store.PNG"  >  
 

# Getting started 

## Compatibility 
Development started since [Interceptor 4.20](https://www.nomanssky.com/interceptor-update/) and has been compatible with every update up to the latest [Voyagers 6.0](https://www.nomanssky.com/voyagers-update/).<br>
I take great care to ensure the intergrity of the database that holds all the stored properties. Rest assured that this data is safe with each coming new update. <br>
<sub>(After all, I use DNA myself and I have no plan to lose my own collection)</sub>
<br>
<br>
Currently only the [Steam](https://store.steampowered.com/app/275850/No_Mans_Sky/)(Windows) and [GOG](https://www.gog.com/game/no_mans_sky)(Windows) platforms are compatible with DNA since these are the only platforms I own the game on. Thus the only platforms I can thoroughly test the app with.
 
## Requirement 
- Make sure you have No Man’s Sky installed.
- Download the latest [release](https://github.com/IzzyTheDreamingFox/FoxTech-DNA/releases) of DNA.
- Unzip the executable somewhere on your pc.
- Run the exe file.
- You’ll be greeted by a short sequence to help you guide through the setup of your preferred platform. <br>
(While the app tries to find the folder automatically, it can, in the case of a custom setup, not find the folders. If this happens you’ll have to set these yourself in the provided form.)
- Once that’s over, you're ready to go!

## Usage

> [!IMPORTANT]
> DNA features an automatic backup system that triggers before any edit is made. Remember that this tool is still early in development and it’s advisable to make your own backups just in case.

The best time to use DNA is before or after your play session. <br>
If you wish to sort your inventory, or transfer ships and do other things, while the game is running please take the following steps to make sure your changes will be saved. <br>
- While in game, save (for example using a save-beacon or entering/exiting a ship) and pause the game (esc-button).
- Switch to the application and reload your save game you wish to edit.
- Make the changes you wish to make and save those changes.
- Go back to the game and reload the most recent save. <br>

If you followed the steps correctly, you should now be playing on the edited save.
 
# Licence 
This free-to-use application (and it will stay that way) is licenced under the copyleft GNU General Public Licence.
[MORE INFO](LICENSE) 

 
# Contact & Support
I have created a [discord](https://discord.gg/fk2BWT7hAd) where you can contact me directly.<br>
I’m always looking for constructive feedback and new ideas for features to implement or on how to further refine the application.<br>
So please, let me know!<br>

For more general help regarding save edits where you can contact me as well as others is the [No Man's Sky - Creative & Sharing Hub](https://discord.gg/QMCTefAD2p).

 
# Author:
IzzyTheDreamingFox
 
# Credits:

- My obsession/frustration for/at No Man’s Sky: Laying the seed for the idea of DNA.

- [goatfungus-NMSSaveEditor](https://github.com/goatfungus/NMSSaveEditor) Being the first save-editor I used to edit the game. Essentially showing me that save-editing this multiplayer game is possible and allowing the seed to grow roots.

- [zencq-NomNom](https://github.com/zencq/NomNom/tree/master) Being the editor that allowed me to edit even more things. Essentially allowing me to break the game and explore the capabilities of save-editing.

- [monkeyman192-MBINCompiler](https://github.com/monkeyman192/MBINCompiler) Without this, DNA probably wouldn't exist. Thanks to this library I was able to extract all the data I needed from the game along with the mapping to deobfuscate save-files.

- Zgarr. The person that had to listen the most to my No Man’s Sky rambling. Without his listening ear I would have probably given up on the whole project.

Special thanks to DHarhan and Mjstral to take the chance and verify the app works on their systems.
