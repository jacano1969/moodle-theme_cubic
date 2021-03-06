CUBIC - MOODLE THEME

DESCRIPTION
-----------

This theme is a base theme for Moodle, which introduces some new concepts and which takes advantage of some new technologies like HTML5 and CSS3.

On the top of every Moodle page, this theme introduces a user bar which provides users with several menus. Each of these menus contain information about the current user courses, activities, notifications, events, messages, settings, and others.

Besides that, this theme is related to two new Moodle local plugins, which introduce the Institutions (https://moodle.org/plugins/view.php?plugin=local_institutions) and the Applications (https://moodle.org/plugins/view.php?plugin=local_applications) concepts in Moodle. On the user bar a menu for each of those concepts is displayed. Those menus allow the users to access institutional or applications web pages, respectively. Both the institutions and the applications pages can be accessed without leaving Moodle.

Furthermore, this theme is also related to a new Moodle block plugin that introduces a chat service for Moodle that is available for everyone, a bit like Google Chat or Facebook Chat (https://moodle.org/plugins/view.php?plugin=block_gchat). 

Since the user bar contains a lot of useful information, the blocks are no longer required in some contexts. For example, when embedding a page, Cubic uses all horizontal and vertical space leaving only the user bar in the top.

Finally, this theme also provides a settings page where you can change several properties like logos, colors, system name, and others. On this page you can also remove the institutions and applications menus from the user bar in case you don't want to use them.


RECOMMENDATIONS
---------------

I changed the name of some Moodle core icons because they didn't make much sense to me, so if you want some icons to display correctly, I recommend that you make the changes listed bellow to your Moodle installation. However, these changes are not mandatory for this theme to work correctly.
	- Replace all occurrences of "t/delete" by "t/close" in the file "lib/javascript-static.js";
	- Replace all occurrences of "t/dockclose" by "t/close" in the file "blocks/dock.js";


CONTENTS ORGANISATION
---------------------

	FOLDERS:
	- javascript: contains all javascript scripts;
	- lang: contains languages files for English and Portuguese (Portugal);
	- layout: contains two layout files:
		- general.php - used for all types of pages in Moodle, with different kind of options;
		- userbar.php - used to create the user bar code (it's not used as a layout file);
	- pix: contains all the images used by this theme which are not part of Moodle;
	- pix_core: contains all the images to replace the Moodle core pictures;
	- pix_plugins: contains all the images to replace the Moodle Activities core pictures;
	- style: contains all the CSS stylesheets.
		
	FILES:
	- ajax.php: file used for all ajax requests. It can only be accessed via ajax by a client and it maps certain strings to certain functions;
	- config.php: theme configuration;
	- lib.php: defines all functions used for layout generation, by ajax requests, and for css processing;
	- settings.php: defines all the theme settings which allow the user to control the system logo, the user bar colours, the use of institutions and applications package and the default course view;
	- version.php: theme version information.

