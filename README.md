# -HOW-TO-Add-items-in-Shops-FiveM
[HOW TO] Add items in Shops FiveM - this time we adding a Hotdog

https://youtu.be/3aAb82SpSbw  <- look at the video! 

Check the codes here: 
https://github.com/geithamsen/-HOW-TO-Add-items-in-Shops-FiveM

What you NEED: 
You have the following: esx_basicneeds, esx_shops and [ESX] Shops UI: https://github.com/NeQYT/esx_shopsui (FREE)

and find a PNG on google for a Hotdog, resize it be exactly 128x128 PX !important
I added mine to the github :) 
Download there: https://github.com/geithamsen/-HOW-TO-Add-items-in-Shops-FiveM/blob/main/hotdog.png

▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽

What you need for this:

Notepad++ or just a notebad, either works.
access to MySQL databases
Access to resources folders:
esx_basicneeds AND esx_shops/html/img
txAdmin for restarting the server/or how ever you restart it.

▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽

Files, MySQL tables to be edited in order.
⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤

1) add the following to _resources.lua:
https://github.com/geithamsen/-HOW-TO-Add-items-in-Shops-FiveM/blob/main/_resources.lua
TIP: You can also add  'html/img/*.png' so that all images will be pulled from resources :)(easy way)


▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽

ITEMS TABLE: MySQL Databases and Tables to add
⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤
1) Go to the table: items
2) Copy the table(just the easy way to do it): bread
3) edit/rename the name to: hotdog
4) edit/rename the label to: Hotdog. -- label is the name that will show on the server
5) click on the bottom: GO

▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽

SHOPS TABLE: MySQL Databases and Tables to add
⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤⌤
1) Go to the table: shops
2) You probably only have 3 or 6 rows here for bread and water. So we are going to add 3 more rows. (if you have images, you can add: img/bread.png - to the bread under the row: imglink -same for water.)
3) Copy the 'TwentyFourSeven' row
4) edit/rename 'item' to: hotdog
5) edit the price if you want to. 
6) imglink you add: img/hotdog.png. 
7) click on the bottom: GO

Repeat this to the: RobsLiquor table and LTDgasoline
so you have 3 new rows with hotdog in the 3 shops. 

▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽

2) add the following to main.lua
https://github.com/geithamsen/-HOW-TO-Add-items-in-Shops-FiveM/blob/main/main.lua

▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽

3) Add this to en.lua
https://github.com/geithamsen/-HOW-TO-Add-items-in-Shops-FiveM/blob/main/en.lua

▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽

Save these files.

▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽

Restart the server and tadaaaa :P 
