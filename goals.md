# Goals/To-Do for Raven

## The Frontend
Create a frontend to make the cms more accessable
### Security
* Make the /admin/ folder that stores the frontend only be accessible w/ a password and username
  * The folder should be stored in the Raven directory and copied into Articles-html with update.py
* Have some secure way to setup those password/username
* Have some sort of cookie to store login token for a period of time

### Frontend Pages

#### Writing Articles GUI
* A way to write articles
* Includes ways to easy add formatting
* Include ways to easy add the following:
  * Embeded Youtube Video
  * Embeded MP4 Video
  * Embeded Audio
  * Easy Latex Insertion w/ MathJax
* Schedule Article Release
* Easy way to add the thumbnail metadata
* Easy way to add not-article tag


#### Editing Articles GUI
* The writing GUI but with the ability to edit allready published articles
  
#### Config Editing GUI
* Boxes to input config data that gets saved to the config files like the name or confing for feed generation
* Menu to discover themes based on a github repo that A-Macaw creates storing zip-files of themes. When you install a theme it unzips it to the config directory and overites all files it needs to.

## The Scripts

### Homepage.py
* Finish it
* Use a bit more complicated fstring that uses configs instead of hardcoding it in the homepage top and homepage bottom.
* Create the file as main.html.


