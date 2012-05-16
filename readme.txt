=== Plugin Name ===
Contributors: JordiPlana
Tags: 404, redirect, redirection, error, http
Requires at least: 2.7.0
Tested up to: 3.3.1
Stable tag: 1.0

== Description ==
This plugin hooks the normal Wordpress workflow in order to determine if the request is processing will cause a 404 HTTP error. In that case it prevents Wordpress to do any other processing and sends the user to the page defined in the plugin options.

A working and simple solution.

For more information about this plugin you can check [the official page](http://jordiplana.com/404-simple-redirect-plugin-for-wordpress "404 Simple Redirect Plugin for Wordpress").

== Installation ==
1. Download the plugin from the Wordpress plugin repository, unzip and upload to the `/wp-content/plugins/` directory.
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Enjoy!

== Frequently Asked Questions ==

**Scenario**
Sites with high volume of content may have some moved, deleted or badly referenced content. This situation will cause a 404 http error.

**Problem**
In high performance sites the previously described situation can be a resource problem. It is not necessary that we load completely the site to show a 404 error page.

**Solution**
Loading a plain HTML page will result easier for our web server than loading a complete CMS instance.

= What does the plugin? =
The plugin hooks the normal Wordpress workflow in order to determine if the request is processing will cause a 404 HTTP error. Then it makes a redirection to the URL defined in the plugin settings.

== Changelog ==
= 1.0 =
* First version