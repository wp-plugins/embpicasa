=== Embed Picasa Album ===
Contributors: marchenko.alexandr
Tags: picasa
Requires at least: 3.3.1
Tested up to: 3.3.1
Stable tag: trunk

Allow insert picasa album into posts and pages via short code.

== Description ==

This plugin add new button to tinymce that allows you insert any of yours albums into post.

No need in downloading your photos into multiple places.

Add entire album into your post in few clicks.

Automatticaly supports by plugins like Lightbox2.

Added template support, if you want custom template just copy `loop-picasa.php` file into your template and modify it as you want.

== Installation ==

###Installing The Plugin###

Extract all files from the ZIP file, **making sure to keep the file structure intact**, and then upload it to `/wp-content/plugins/`. This should result in multiple subfolders and files.

Then just visit your admin area and activate the plugin.

**See Also:** ["Installing Plugins" article on the WP Codex](http://codex.wordpress.org/Managing_Plugins#Installing_Plugins)

###Plugin Configuration###

To configure this plugin, visit it's settings page. It can be found under the "Settings" tab in your admin area, titled "Picasa".

###Templating###

To make custom template for your gallery just copy `loop-picasa.php` file into your template.


== Frequently Asked Questions ==

= How to open images in lightbox =

Just install something like [lightbox](http://wordpress.org/extend/plugins/lightbox-2/) plugin it will automaticaly open all images in lightbox

= How to theme result =

Just copy `loop-picasa.php` file into your template.

== Screenshots ==

1. Plugin configuration page.
2. TinyMCE, the plugin's buttons, and the plugin's dialog window.
3. Result on page.

== Changelog ==

= 1.0.0 =
* Initial commit.

== Upgrade Notice ==

= 1.0.0 =
Initial commit.

= 1.0.1 =
Added title to anchor and alt to image.

= 1.0.2 =
Fixed bug with full size options.