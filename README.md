# -HOW-TO-Add-items-in-Shops-FiveM
[HOW TO] Add items in Shops FiveM - this timne we adding a Hotdog

https://youtu.be/3aAb82SpSbw  <- look at the video! 

You have the following: 
esx_basicneeds, esx_shops and [ESX] Shops UI(https://github.com/NeQYT/esx_shopsui) (FREE)

Before you begin: 
Add the following lines in _resources.lua(https://github.com/geithamsen/-HOW-TO-Add-items-in-Shops-FiveM/blob/main/_resources.lua)

You can also add e.g: 	'html/img/*.png' so that all images will be pulled from resources :)(easy way)

What you need for this:

1) Notepad++ or just a notebad, either works. 
2) access to MySQL databases
3) Access to resources folders: 
 - esx_basicneeds AND esx_shops/html/img
4) txAdmin for restarting the server/or how ever you restart it. 

Alright: first thing we are going to add the following to the following databases:
Go MySQL -> servers databases -> items: 
find 'bread' -> copy -> name: hotdog | label: Hotdog
(Name will be pulled to database | label will be shown in the game)

///////////////////////////

GO TO: ITEMS 
CLICK COPY E.G BREAD
(LIKE I DO HERE) - look at the video

///////////////////////////

NAME: THE ITEM THAT SHOPS WILL PULL FROM DATABASE
LABEL: WHAT WILL SHOW FOR USERS IN THE SHOP. 

SO ADD 'hotdog' as name and Hotgod as label - AND CLICK GO


///////////////////////////

GO TO SHOPS DATABASE
COPY THE 3 SHOPS AND 
ADD THE FOLLOWING IN THE VIDEO. 

RENAME "ITEM" TO HOTDOG
ADD UR PRICE
AND IMGLINK TO WHERE YOU HAVE 
THE PNG IMAGE STORED - I GOT MINE IN:
\resources\[legacy]\[esx_addons]\esx_shops\html\img


///////////////////////////

REMEMBER TO EDIT THE ID'S!! 

///////////////////////////

HERE WE ADD THE SHOP ITEM! 
REMEBER THE TABLE WE ADDED TO
ITEMS DATABASE: HOTDOG. 
WE WILL USE THIS HERE ALSO. 
THIS FILE IS LOCATED: 
\resources\[legacy]\[esx_addons]\esx_basicneeds\server\main.lua

///////////////////////////


IN THIS FILE YOU ADD THE ANNOUNCEMENT
FOR THE USING AN ITEM, E.G HOTDOG. 
IN THE LOCALES FOLDER. 

THIS IS LOCATED: 
\resources\[legacy]\[esx_addons]\esx_basicneeds\locales\en.lua

and thats it .

Save and restart the server. 


