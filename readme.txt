=== Social Icons Widget ===
Contributors: dannisbet
Tags: social, media, widget, follow, profile, icons, twitter, facebook, linkedin, forrst, dribbble
Donate link: http://dannisbet.com/
Requires at least: 3.5.1
Tested up to: 3.6-beta1-23930
Stable tag: 2013.04
License: GPLv3 or later
License URI: http://www.gnu.org/licenses/gpl-3.0.html

Displays a list of social media website icons and a link to your profile.

== Description ==

The Social Media Icons widget takes a simple, extendable approach to displaying links to your social media profiles in WordPress. The purpose of this plugin was to strip away the complexities I found most other plugins to have and simply display a set of basic social icons in an unordered list. There's no frills and no fanciness, making it easy to style to your website's look.

= Extending =

Developers can easily extend the plugin to accept additional website profiles and upload custom icons to replace the default set. The widget settings allow for three different sizes by default and users can choose to display a label next to each icon.

By default, the Social Icons Widget provides a variety of popular social media websites. However, it's been structured to allow for easy addition of new social media profiles, or removal of unwanted ones.

To edit the list of social media profiles, open social-media-icons-widget.php and locate line 32, which contains the $social_accounts array. Any edits made to this array will be reflected through the entire widget. There's no need to find/replace in any other file.

The structure of the array follows a simple format:

'Full Website Name' => 'full-website-id'

The full-website-id should reflect the name of the image you create in each of the icon folder sizes, or in your custom icon directory. It is also used to populate the class field of the icon when the widget displays. The Social Icon Widget looks for .gif, .jpg, .jpeg, and .png in order and returns the first extention it finds.

The widget can also be branched via its [GitHub page](https://github.com/dannisbet/social-icons-widget).

= Custom Icons =

Custom icons are easy to add. To enable them, select "Custom" from the Icon Type dropdown in the widget settings. In the directory of your active theme, create a folder titled 'social_icons'. Within that directory, add folders titled 'small', 'medium', and 'large' for each icon size you wish to use. Add your icons in .gif, .jpg, .jpeg, or .png format, using the name of the ID in the $social_accounts array (details above).

= Icons =

Default icons are from the Social Boilerplate Iconset created by [Mosaic Web Studios](http://mosaic.ws/projects/boilerplate.php).

== Installation ==

Download the zip file and upload to your WordPress installation. Upon activation, widget is available under Appearance > Widgets. Drag the widget into your sidebar, adjust the settings, and populate the profiles you wish to show on your website.

== Frequently Asked Questions ==

Coming soon.

== Screenshots ==

1. Some examples of how the plugin displays by default in its various settings available via the widget.
2. Widget settings via the Appearance > Widgets screen.

== Changelog ==

= trunk =
* Initial commit

= 2013.04 =

* Initial commit

== Upgrade Notice ==

= 2013.04 =
Initial commit to WordPress plugin repository