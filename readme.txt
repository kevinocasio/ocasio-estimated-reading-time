=== Ocasio Estimated Reading Time ===
Contributors: ocas
Tags: reading time, read time, estimated reading time, reading time bar, blog reading time
Requires at least: 5.8
Tested up to: 6.7
Stable tag: 1.0.0
Requires PHP: 7.4
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Automatically calculates and displays a clean estimated reading time on your blog posts to set visitor expectations.

== Description ==

Long blog posts without a clear time guide can make readers click away before they start reading.

Ocasio Estimated Reading Time automatically figures out how long it'll take someone to read your post. It counts your words based on a standard 250 words per minute speed and shows a clean read time badge right above your post content.

You can also drop the `[reading-time]` shortcode anywhere in your content, custom block layouts, or sidebar widgets.

No heavy JavaScript libraries, no external font requests, and zero database clutter.

== Installation ==

1. Upload the `ocasio-estimated-reading-time` folder to your `/wp-content/plugins/` directory, or install it directly through your WordPress admin screen.
2. Activate the plugin through the 'Plugins' menu in WordPress.
3. Manage the active state directly from the **Ocasio Plugins -> Dashboard** menu in your admin sidebar.

== Frequently Asked Questions ==

= How does it calculate reading time? =
It counts the plain text words in your post and divides them by 250 words per minute (the standard average adult reading speed).

= Can I turn off the automatic display and place it manually? =
Yes. Toggle off the active state in the dashboard and drop the `[reading-time]` shortcode anywhere you want it.

= Does this slow down my website? =
No. It doesn't load heavy JavaScript, external fonts, or bulky tracking scripts. It calculates reading time instantly in lightweight PHP during page load.

= Does it alter my database? =
No. It only reads your post content dynamically on the front end and doesn't change your saved post HTML in the database.

== Changelog ==

= 1.0.0 =
* Initial public release.
* Automated reading time calculation at 250 words per minute.
* Front-end content filter with auto-display toggle.
* `[reading-time]` and `[reading_time]` shortcodes for manual placement.
* Integrated into the unified Ocasio Plugins suite dashboard.
