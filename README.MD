© 2026  NZXY-Proyect  
This software is licensed under Creative Commons BY‑NC‑ND 4.0.


### Link-P Manual and Help Resources Current Version: 1.020.4 (First Public Release)

--

What is p-link / Peritus Link?
Peritus Link is personal software that allows you to store a list of links (Web Addresses), each accompanied by a thumbnail to help you more easily identify your saved content.



Basic Functionality:

To add new notes, simply press the "Add-note" button located in the bottom-right corner.
Next, add a title, a link, and tags. Tags are not a separate, critical feature; in fact, only the URLs serve a true functional purpose. Furthermore, the app does not validate whether you have entered a valid URL or not—it simply treats the input as text that will be copied or sent to your browser to open, depending on the action you execute via the (Toolbar).

Cards/Notes: Each of your notes, or "Cards," possesses several properties, such as:

-Toolbar
+
+Copy Button
+Open in Browser Button
+Move Up (Order) Button
+Move Down (Order) Button
+Pin Button (This function simply moves the card to the very first position, given that—within this app—pinning is essentially automatic and determined by positional order.)

-Thumbnail

Continuing with the basic functions: Metadata Search. The various text fields—such as title, description, or tags—which otherwise serve no distinct function, exist specifically for search purposes. You can find the search bar in the top-right corner. The search operates in real-time: you can enter a search term and watch as the display area—where your cards are shown—filters the results instantly based on your input in the search bar. (Remember that tags and descriptions—just like the title—do not possess any advanced functionality or formatting; you are free to organize or write them however you wish.)

Card Options:
The final basic feature involves the card options, accessed via a context menu. Simply right-click on any card to delete or edit it.

App/Software Settings:
Password Protection: To lock your app with a password, simply click on the application's title (Peritus - Link). ) Here, you will find the "About this app and configs" window, where you can create a new password if you do not already have one. Simply click the "Lock with password" button, and then, in the pop-up form, set your password and repeat it to confirm.

Thumbnail Style:
Thumbnails (preview images for URLs) typically use the "Elegant Crop" style. This strikes a balance between the overall size of the thumbnail display area and decent image quality or visibility. However, if this style does not appeal to you and you prefer greater functionality—specifically, viewing the entire thumbnail without cropping, while still having it fit comfortably and proportionally within the card area—you can switch to the "Full-Fit" option.

Small Tips and Tricks:

#Removing a Password:
If, for any reason, you no longer wish to password-protect your app, simply navigate to the directory where the app is stored and delete the "User.Protectoris" file; the app will automatically unlock.

**Adding or Editing Custom Thumbnails:**
The thumbnail system is easily customizable. If a specific URL fails to provide a thumbnail, or if you simply prefer to create or edit one yourself, all you need to do is place the image you wish to use as a thumbnail into the "thumbs" folder located alongside the executable file (.exe). The image must be in JPG format, and you must rename it to exactly match the Title you assigned to your card or note. Close and then reopen the app, and the thumbnail will load automatically. The thumbnail system is semi-autonomous; it does not require constant maintenance. For example, if you wish to copy your app—along with just your "notes database"—to another device, or if you only have the "notes database" file itself, simply place the database file in the same folder as the executable. Upon launching the app, it will automatically retrieve thumbnails for all your URLs (provided they have them), download them using the respective titles of your cards, and simultaneously load those images as thumbnails.

**Card/Note Database:** 
— Where your settings and all your notes are stored:
This file contains *all* your cards, easily readable using any text editor. The file located alongside your executable—named "data.peritus"—is all you need to keep your personal notes safe; this single file is sufficient to safeguard all your information. **The default internal structure of this database is as follows:**

`For Settings:`

//CONFIG
THUMB_MODE:
ENDCONFIG

`And for Cards:`

//BEGIN
URL:
TITLE:
DESC:
TAGS:
END



If you would like to find more applications like this one,
You can follow us on itch.io, X (Twitter), and YouTube.

NZXY 2026
