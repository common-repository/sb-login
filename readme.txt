=== SB Login ===
Contributors: Fida Al Hasan
Donate link: http://science-breeze.com
Tags: sb login, sb, login, sidebar login widget, user login widget, user registration, custom login widget, login widget, science breeze, fida al hasan, widget, register, cool, bangla, recent activity
Requires at least: 2.8
Tested up to: 3.6
Stable tag: 2.5

Sb login widget that allows a user to login, register, reset their password, see recent activity,time,post and comment count in one place.

== Description ==

Sb login widget that allows a user to login, register, reset their password, see recent activity,time,post and comment count in one place.

= Features = 

*	A login and registration widget for your blog
*	Tabs/links for logged out users include login, register, and 'lost password'.
*	Logged in users can see their name, avatar, last logged in date, recent activity, and comments/posts since last sign in.
*	AJAX validation makes this thing run smooooth
*	Callable from a function in case you hate widgets

Why dont you rate the plugin if you like it !! :)  >> 
 
My other plugin [Fida Al Hasan](http://profiles.wordpress.org/fida02/).

== Installation ==

= Automatic =

* In the admin panel plugins page click Add New
* Search for SB Login 
* Find SB Login in the list an click Install Now
* Click OK when prompted
* Enjoy!

= Manual =

* Extract sb-login.zip to your wp-content/plugins directory.
* In the admin panel under plugins activate SB Login.
* Enjoy!

= Usage, As a function instead of a widget =

Add the function nd_login_widget( $args ); to your theme. $args is optional and can can take an array of options (before_title, after_title, before_widget, after_widget).

= Styling = 

You may want to style the widget to make it match your theme; to do so you have one options. 
	
	* Edit css/login.css in the plugin (be sure to back this up if you ever update the plugin). 

== Frequently Asked Questions ==

= Widget not working? =

* Most *good* themes contain the required wp_head/wp_footer hooks - if yours does not you will need to slap your developer on the back of the head and add them to your theme's header and footer.php files.

http://codex.wordpress.org/Plugin_API/Action_Reference/wp_head
http://codex.wordpress.org/Plugin_API/Action_Reference/wp_footer

Basically, add: <?php wp_head(); ?> in header.php and <?php wp_footer(); ?> in footer.php.

* If you use W3total cache don’t enable java script minify and Inline JS minification 

== Screenshots ==

1. Login tab.
2. Registration tab.
3. Example logged in user 1 .
4. Example logged in user 2 .
5. Widget

== Changelog ==

1.0 - First Release 
1.1 – Bug fix

