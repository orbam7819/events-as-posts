=== Events as Posts ===

Contributors: orbam7819
Donate link: https://paypal.me/ambrogiopiredda
Tags: event, events, event list, agenda
Requires at least: 4.0.24
Tested up to: 4.9.8
Stable tag: 0.1
Requires PHP: 7.0
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

A simple plugin that allows you to post events on your site

== Description ==

**Events as Posts** is a simple plugin that allows you to post events as if they were normal posts, but with added fields like date and location.

It also allows you to display **lists of events** everywhere on your site using a shortcode. You can choose if you want to display future, past or all the events, and also the number of events and of which category.

Other features include:

* 3 layouts for the list of events (1, 2, and 3 columns)
* Settings for text color of location, date, time and categories
* A stylesheet to iclude your own custom styles

**Languages**

* English
* Spanish

== Installation ==

**Installation via WordPress**

1. Go to the menu 'Plugins' -> 'Install' and search for 'Events as Posts'
2. Click 'Install'

**Manual Installation**

1. Upload 'events-as-posts' directory to the '/wp-content/plugins/' directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Go to 'Events' -> 'Add event' in the admin menu to publish your events
4. Go to 'Events' -> 'Settings' in the admin menu to create a shortcode for a list of events and add styles to it

== Frequently Asked Questions ==

= When I choose to display events by category they are not showing. =

Double check that you have written the category name correctly and, if you have more than one category, that you have separated them with a comma.

= I chose to display the excerpt in a list of events and it's showing in all the lists, how can it be? =

The setting that allows you to show the excerpt on lists of events is not related to the shortcode
and if selected it will show the excerpt on all the lists.

= Can I change the order of how events on the list are displayed? =

Yes, just add to the shortcode `order="ASC"` for ascendent order or `order="DESC"` for descendent order.

== Screenshots ==

1. Event post with date, time and location
2. Add a new event as if where a normal post
3. Order events by date in admin menu
4. List of events settings
5. List of events


== Changelog ==

= 0.1.? =
'Link to location' field in 'Event' -> 'Add event' makes sure you're entering a URL and not something else.

= 0.1 =
* First release.