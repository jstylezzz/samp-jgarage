About
-----

I received some requests for a dynamic garage system, using Dini to save files. After some time of work, I finished it. Now, I know Dini is not the most used and most advanced file processor out here, but as I specifically got asked to use Dini, I used it. Since 5/12/14 there's a universal script available, holding a dini, y_ini, MySQL and SQLite version. It also has 'strcmp command' mode and 'zcmd' mode.
Basically, this script lets you create garages for players to store their vehicles in. Each garage has it's own virtualworld, which means they won't see eachother in different garages. As Rcon, you can create and remove garages. As normal player, you're able to buy a garage, sell your garage, lock it, and store your vehicles in it.

> **Note**: This script does not save vehicles. You'll need a vehicle system
> which saves the virtualworld and interior of the car, otherwise it
> won't load properly.

----------

Installation
-----


1. Place jGarage.amx in your filterscripts folder
2. Extract the scriptfiles folder from the archive. It contains the required folders, and the database file for the SQLite data.
3. Add jGarage to the filterscripts line in your server.cfg (Note: it's cAsE SensiTive!)
4. If you use the MySQL system, be sure to add the plugin to the plugins line.
5. The default saving system is SQLite. If you want to use another saving system, open up the .pwn and check the systematic configuration section.
6. *If you're using the MySQL R6 version, be sure to upload the SQL dump to your database.


----------
