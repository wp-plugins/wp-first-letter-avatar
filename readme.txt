=== WP First Letter Avatar ===
Plugin Name: WP First Letter Avatar
Version: 1.2.5
Plugin URI: https://github.com/DanielAGW/wp-first-letter-avatar
Contributors: DanielAGW
Tags: avatars, comments, custom avatar, discussion, change avatar, avatar, custom wordpress avatar, first letter avatar, comment change avatar, wordpress new avatar, avatar 
Requires at least: 3.0.1
Tested up to: 4.1.1
Stable tag: trunk
Author: Daniel Wroblewski
Author URI: https://github.com/DanielAGW
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Set custom avatars for users with no Gravatar. The avatar will be a first (or any other) letter of the users's name.

== Description ==

WP First Letter Avatar **sets custom avatars for users without Gravatar**. The avatar will be a first letter of the users's name, just like in [Discourse](http://www.discourse.org/). You can also configure plugin to use any other letter to set custom avatar.

WP First Letter Avatar includes a set of **beautiful, colorful letter avatars** in many sizes. Optimal size will be chosen by the plugin in order to display high quality avatar and not download, for example, big 512px avatars when only 48px is needed... **PSD template** for avatar is also included.

You can also create your own avatar set by creating new directory next to *'default'* folder and following the naming convention from *'default'*. Keep in mind that your avatar set will be deleted after updating plugin!

By default, custom avatar will be set only to users without Gravatars, but you can change that in settings and not use Gravatar at all.

WP First Letter Avatar helps you **bring more colors** into your blog. Plus, your readers will be more **willing to comment on your posts**, since they can actually relate to these avatars much better than to Monsters or Mystery Man.

All images were compressed using the fantastic [TinyPNG](https://tinypng.com/), so avatars are **incredibly light and ultra-high quality**.

You can [fork the plugin on GitHub](https://github.com/DanielAGW/wp-first-letter-avatar).

= Compatibility with other plugins =
WP First Letter Avatar is fully compatible with [bbPress](https://bbpress.org/). For [BuddyPress](https://buddypress.org/) compatibility please use my other plugin - [BuddyPress First Letter Avatar](https://wordpress.org/plugins/buddypress-first-letter-avatar/).

== Installation ==

= From WordPress dashboard =

1. Go to *'Plugins > Add New'*.
2. Search for *'WP First Letter Avatar'*.
3. Activate *'WP First Letter Avatar'* in *'Plugins'* page.
4. Plugin works right out of the box. For additional configuration, go to *'Settings > WP First Letter Avatar'*.

= Manual installation =

Extract the zip file and drop the contents in *'wp-content/plugins/'* directory of your WordPress installation, then activate the Plugin from *'Plugins'* page.

== Frequently Asked Questions ==

= Can I change custom avatars? =

Absolutely! Just create new directory in 'images' directory, call it, for example 'my_avatar_set' and change the avatar set in settings. Make sure to follow the directory and filename convention. 
NOTE: Your custom avatars WILL BE DELETED after updating the plugin! Make backup! 

= Can I set custom avatars based on last (or any other) character in user's name? =

Of course! This can be done in plugin settings.

= I don't want to use Gravatar at all. Can I disable it? =
Yes! By default, WP First Letter Avatar sets custom avatar only to users without Gravatar, but in plugin settings you can disable it and use custom avatar for everybody.

= Can avatars be round, like in Google+? =
Yes - just go to plugin settings and click Round avatars.

== Screenshots ==

1. This shows three comments with first letter avatars (these commenters don't have their Gravatars) and one with standard Gravatar.
2. Two comments with custom first letter avatars.
3. Set of alphabet avatars in WP First Letter Avatar.
4. Very simple settings page for WP First Letter Avatar. You can decide which character should be used to specify avatar, turn off Gravatar, use custom avatar sets, use rounded avatars etc.

== Changelog ==

= 1.2.5 =
* Fixed common PHP warning
* Fixed avatar presentation of logged-in users in their userbars

= 1.2.4 =
* Fixed couple of small technical issues

= 1.2.3 =
* Improved avatar appearance on top admin/user bar
* Added full compatibility with bbPress plugin

= 1.2.2 =
* Fixed conflicts with some comment systems (such as wpDiscuz)

= 1.2.1 =
* Avatar is now in the right position in dashboard (in previous versions it used to be in bottom left corner instead of upper right corner)
* Optimized database readings (for plugin settings)

= 1.2 =
* Added round avatars option - you can turn it on in plugin settings

= 1.1 =
* Fixed PHP "Missing argument" error

= 1.0 =
* First WP First Letter Avatar release

== Upgrade Notice ==

= 1.2.5 =
This version fixes annoying PHP warning. Update recommended.

= 1.2.4 =
This version fixes couple of small technical issues. No need to update unless you have experienced any problems with the plugin.

= 1.2.3 =
This version introduces full compatibility with bbPress and fixes some issues with avatars on user/admin bar. Update recommended.

= 1.2.2 =
This version fixes conflicts with some comment systems (such as wpDiscuz) and slightly improves plugin performance. Update recommended.

= 1.2.1 =
This version fixes avatar placement in user dashboard and improves database reads - update as soon as possible.

= 1.2 =
Added new feature (rounded avatars, can be turned on in plugin settings). Update not necessary.

= 1.1 =
This version fixes a PHP "Missing argument" error - upgrade as soon as possible.

= 1.0 =
First WP First Letter Avatar release.