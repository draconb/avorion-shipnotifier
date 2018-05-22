# Ship Notifier for Avorion
Displays a customizable list of ships in a sector for the game Avorion


Features:

* Shows all ships in sector
* Filter out Civilian and/or Friendly ships
* Select ship by left or right clicking on the list (Warning, left mouse WILL fire weapons!) I recommend using right click.
* Choose faction relation level to consider "friendly"


Pre-Reqs: [MoveUI by Dirtyredz (v2.1.1)](https://github.com/dirtyredz/MoveUI)

Server side requirements: **Yes**

Client side requirements: **Yes**

Install:

Download the file. Unzip "**ShipNotifier.lua**" to your **avorion/mods/MoveUI/Scripts/player** folder

Edit **avorion/mods/MoveUI/config/MoveUIConfig.lua** and add the following down with the others:

    MoveUIConfig.AddUI("ShipNotifier", false)

Where you add it is where it will show up on the main MoveUI screen. I personally put it under "FactionNotifier" since that deals with adding sector faction info and this adds the ship details.

Here is an example video of it in action:

https://youtu.be/XM05OEUwhPo

Download:

https://github.com/draconb/avorion-shipnotifier/releases

Download the source code and then unzip the mods folder to your steamapps\common\avorion\mods

Should look like:

steamapps\common\avorion\mods\MoveUI\scripts\player\ShipNotifier.lua

and have a few other files from MoveUI already in that folder such as FactionNotifier.lua. If you don't, its in the wrong spot!

TODO:

Figure out if there is a way to cancel mouse button events so middle mouse button can be used for target selection (it selects then deselects since the mouse isn't over a target)

More options?

Improve contrast? Hard to see depending on the sector / lighting. I added a slight drop shadow to help
