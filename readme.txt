=== Available URL ===
Contributors: mjkhajeh
Donate link: https://zarinp.al/@zantium
Tags: url,available url,availableurl,urls,demo creator,create demo,user urls,role urls,admin
Requires at least: 5.0
Tested up to: 5.8.3
Stable tag: 1.4.5.0
Requires PHP: 7.0
License: WTFPL
License URI: https://en.wikipedia.org/wiki/WTFPL

Let users just view urls you want. And create demo for your plugins & themes easily.

== Description ==

By Available URL you can add urls and force users or roles just see these urls. If a user(logged in user) open a URL that not allowed, Will redirect to a URL you want. You can enter redirect URL for backend and frontend separately.
Most used of this plugin will be in create demo for plugins & themes. You can install it on WordPress network and create multiple demo.

Available URL has some hooks for programmers. Also when a URL redirected, In location URL will be a request called: 'redirect_by' this will be useful for sometimes.

= Emergency reset =
In 1.3.2.7 I added a emergency way for disable admin redirects.
For use that, Just open this URL(Before that, Replace "example.com" with your domain):
`http://example.com?availableurl_reset_admin=true`

= One more thing about Available URL: =
Available URL uses i18n, So you can translate it for your language.

You can use [GitHub](https://github.com/mjkhajeh/available-url) plugin page to development it.

== Changelog ==
= 1.0.0.0 =
* First release of available URL

= 1.3.2.7 =
* Change and Fix bugs in redirect function
* Change URL settings
* Fix translates
* Fix bug of "New Row" button
* Functions are now optimized
* Add emergency reset for admins 

= 1.4.5.0 =
* Tested up to WP 5.8.3
* Optimize code
* Fix translation

== Installation ==

1. Upload the plugin files to the `/wp-content/plugins/available-url` directory, or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the 'Plugins' screen in WordPress
3. After activate Available URL, In wordpress settings will be a submenu that called: Available URL. From there you can enter your URLs by role and user filter.

== Screenshots ==

1. Available URL Dashboard.