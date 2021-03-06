=== Connections Business Directory Hours ===
Contributors: shazahm1@hotmail.com
Donate link: http://connections-pro.com/
Tags: addresses, address book, addressbook, bio, bios, biographies, business, businesses, business directory, business-directory, business directory plugin, directory plugin, directory widget, church, contact, contacts, connect, connections, directory, directories, hcalendar, hcard, ical, icalendar, image, images, list, lists, listings, member directory, members directory, members directories, microformat, microformats, page, pages, people, profile, profiles, post, posts, plugin, shortcode, staff, user, users, vcard, wordpress business directory, wordpress directory, wordpress directory plugin, wordpress business directory, business hours, widget
Requires at least: 4.2
Tested up to: 4.8
Stable tag: 1.0.7
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Extension for the Connections Business Directory that adds the ability to add business hours to an entry.

== Description ==

This is an extension plugin for the [Connections Business Directory Plugin](http://wordpress.org/plugins/connections/) please be sure to install and active it before adding this plugin.

What does this plugin do? It adds the ability to add hours of operation to entries.

Business hours can be entered for each day of the week, and if needed multiple hours open/close periods can be added per day.

It comes with a widget that will display only on the detail view of a single entry. The widget can be configured to show a "We are currently open." status message and highlight the current open period as well as either displaying a "Closed Today" message or simply not showing the closed day.

The business hours can also be optionally shown within the entry card in both the results list view and single entry detail view.

[Checkout the screenshots and video of this plugin in action.](http://connections-pro.com/add-on/hours/)

Here are other great extensions that enhance your experience with the Connections Business Directory:

* [Toolbar](http://wordpress.org/plugins/connections-toolbar/)
* [Login](http://wordpress.org/plugins/connections-business-directory-login/)
* [Income Level](http://wordpress.org/plugins/connections-business-directory-income-levels/)
* [Education Level](http://wordpress.org/plugins/connections-business-directory-education-levels/)
* [Languages](http://wordpress.org/plugins/connections-business-directory-languages/)

== Installation ==

Extract the zip file and just drop the contents in the wp-content/plugins/ directory of your WordPress installation and then activate the Plugin from Plugins page.

== Frequently Asked Questions ==

None yet....

== Screenshots ==

[Screenshots can be found here.](http://connections-pro.com/add-on/hours/)

== Changelog ==

= 1.0.7 06/29/2016 =
* BUG: `<th>` tags should be within `<tr>` tags.
* OTHER: Readme tweaks.
* I18N: Add Dutch (Netherlands) translation.
* DEV: Update .gitignore.

= 1.0.6 05/05/2015 =
* BUG: Add missing text domain to "Business Hours" so it is translatable.
* BUG: Correct text domain in the widget.
* BUG: Fix filters for language files.
* TWEAK: Comment out unused activation/deactivation hooks since they are not used.
* I18N: Add Swedish (Sweden) translation.
* I18N: Update POT file.

= 1.0.5 05/01/2015 =
* BUG: Load plugins textdomain on plugins_loaded action hook.
* BUG: Make two missed strings translation ready.
* BUG: Empty string should not be run thru gettext.
* TWEAK: Add POT file for translation.
* TWEAK: Add Income Level link to readme.txt.

= 1.0.4 07/14/2014 =
* TWEAK: If no open hours have been set for any day or any periods within a day, do not show the open hours content block.

= 1.0.3 06/05/2014 =
* BUG: The front-end CSS file was not being enqueued if Form was not installed and activated.

= 1.0.2 05/30/2014 =
* TWEAK: CSS tweak for better Form 2.0 integration.

= 1.0.1 05/26/2014 =
* TWEAK: Refine CSS and JS enqueueing logic. Requires Connections >= 0.8.9.

= 1.0 05/03/2014 =
* Initial release.

== Upgrade Notice ==

= 1.0 =
Initial release.
