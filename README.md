# WP Breadcrumbs CB
This plugin for show breadcrumbs on your wordpress website, this plugin working for post,pages,custom post type, custom taxonomy, category, date archive, taxonomy archive, date archive, and more, just need to css for showing your own style.


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
