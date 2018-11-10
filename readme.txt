=== WP Breadcrumbs CB ===
Contributors: hmbashar
Donate link: http://donate.codingbank.com/
Tags: breadcrump, post,pages,custom post type, custom taxonomy, category, date archive, taxonomy archive, date archive, and more
Requires at least: 4.6
Tested up to: 5
Stable tag: 1.0
Requires PHP: 5.2.4
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

This plugin for show breadcrumbs on your wordpress website, this plugin working for post,pages,custom post type, custom taxonomy, category, date archive, taxonomy archive, date archive, and more, just need to css for showing your own style.

== Description ==

This plugin for show breadcrumbs on your wordpress website, this plugin working for post,pages,custom post type, custom taxonomy, category, date archive, taxonomy archive, date archive, and more, just need to css for showing your own style. function name here 
```	<?php 
		if(function_exists('wp_breadcrumbs_cb')) {
			wp_breadcrumbs_cb();
		}
	?>
```
default css coming soon with next version.

== Installation ==

This section describes how to install the plugin and get it working.

e.g.

1. Upload the plugin files to the `/wp-content/plugins/plugin-name` directory, or install the plugin through the WordPress plugins screen directly.
1. Activate the plugin through the 'Plugins' screen in WordPress
1. Use the Settings->Plugin Name screen to configure the plugin
1. (Make your instructions match the desired user flow for activating and installing your plugin. Include any steps that might be needed for explanatory purposes)


== Frequently Asked Questions ==

= How to use this plugin? =

just use this function where you want to show breadcrumbs
```
	<?php 
		if(function_exists('wp_breadcrumbs_cb')) {
			wp_breadcrumbs_cb();
		}
	?>
```
= Doesn't show style? =

Right now only function working, donn't have any css, you need to write your own css match with your theme.
default css coming soon with next version.

== Screenshots ==

1. This screen shot description corresponds to screenshot-1.(png|jpg|jpeg|gif). Note that the screenshot is taken from
the /assets directory or the directory that contains the stable readme.txt (tags or trunk). Screenshots in the /assets
directory take precedence. For example, `/assets/screenshot-1.png` would win over `/tags/4.3/screenshot-1.png`
(or jpg, jpeg, gif).
2. This is the second screen shot

== Changelog ==

= 1.0 =
* A change since the previous version.
* Another change.

= 0.5 =
* List versions from most recent at top to oldest at bottom.

== Upgrade Notice ==

= 1.0 =
Upgrade notices describe the reason a user should upgrade.  No more than 300 characters.

= 0.5 =
This version fixes a security related bug.  Upgrade immediately.

== Arbitrary section ==

You may provide arbitrary sections, in the same format as the ones above.  This may be of use for extremely complicated
plugins where more information needs to be conveyed that doesn't fit into the categories of "description" or
"installation."  Arbitrary sections will be shown below the built-in sections outlined above.

== A brief Markdown Example ==

Ordered list:

1. Some feature
1. Another feature
1. Something else about the plugin

Unordered list:

* something
* something else
* third thing

Here's a link to [WordPress](http://wordpress.org/ "Your favorite software") and one to [Markdown's Syntax Documentation][markdown syntax].
Titles are optional, naturally.

[markdown syntax]: http://daringfireball.net/projects/markdown/syntax
            "Markdown is what the parser uses to process much of the readme file"

Markdown uses email style notation for blockquotes and I've been told:
> Asterisks for *emphasis*. Double it up  for **strong**.

`<?php code(); // goes in backticks ?>`