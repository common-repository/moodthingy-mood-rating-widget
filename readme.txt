=== MoodThingy Mood Rating Widget ===
Tags: widget, plugin, stats, statistics, ratings, rating, poll, vote, voting, mood, emotion, feeling, feedback, comments
Contributors: moodthingy, ernieatlyd, mikeleeorg
Tested up to: 3.5
Requires at least: 2.9
Stable Tag: 1.2

Adds a one-click real-time mood rating widget to all of your posts.

== Description ==

MoodThingy is a plugin that any blogger can use to track the emotional feedback (Fascinated, Amused, Sad, Angry, Bored or Excited) of an individual blog post or article. The plugin can be configured to automatically appear below all of your posts, or manually placed anywhere within a post using a handy WordPress tag. A dashboard of MoodThingy stats is also offered so you can see which articles excite, amuse, or bore your readers, sorted by a particular mood or number of votes in the past day, week, or month.

A WordPress Widget is also included in the plug-in as a way to show readers the most popular blog posts or a particular mood, or in the past day, week, month or year. 

MoodThingy PRO has additional features:

*   Customize the mood text without having to edit the plug-in code, as well as the amount of moods. (Maximum number of six)
*   Customize the other text in the MoodThingy plug-in
*   Customize the mood colors

<a href="http://codecanyon.net/item/moodthingy-mood-rating-widget-for-wordpress-pro/2255966?ref=ErnieAtLYD">Grab a copy of MoodThingy PRO</a>!

NOTE: If you have made changes to the plug-in code, be sure to make a back-up before upgraded to new versions!

== Installation ==

1. Download and unzip the plugin file.
2. Upload the "moodthingy" folder into your /wp-content/plugins/ directory.
3. Go to the Plugins section of your WordPress admin and activate the MoodThingy plugin.
4. And you're done!

== Frequently Asked Questions ==

If you have any questions, you can visit our [UserVoice forum](http://moodthingy.uservoice.com/) or email us at support@moodthingy.com.

== Screenshots ==

1. MoodThingy Plug-in on a Blog Page
2. MoodThingy Settings Page, Stats Tab 
3. MoodThingy Widget on WordPress Widgets Page
4. MoodThingy Settings page, Settings Tab

== Changelog ==

= 1.2 =
* Now added the ability to share through Facebook. In the UI, the option to allow Twitter has been replaced with a general social media sharing option that will let you share via Twitter and Facebook.

= 1.1 =
* Minor copy changes

= 1.0 =
* Added more widgets that can be displayed in a blog through the Widgets menu under Appearances.
* Fixed a bug where single quotes in the CSS placed in the "Additional CSS box" were getting unnecessarily escaped.
* I think this has been out long enough that we can consider this a beta instead of an alpha.  :)

= 0.9.6 =
* Some blogs export magic quotes as extended HTML entities. Convert these to regular characters when you try to tweet.

= 0.9.5 =
* Fixed a bug where "Show a sparkline (graphical bar graph) above moods." wasn't working

= 0.9.4 =
* Added the ability to include image thumbnails in the MoodThingy widget
* Changed some of the text inside the WordPress plug-in directory and added screenshots 3 and 4

= 0.9.3 =
* Fixed a bug where more than one vote was not being recorded in the polls. 

= 0.9.2 =
* Fixed a different SQL Injection vulnerability. Hat tip to Lars Wiebusch at Secunia Research for finding this. 

= 0.9.1 =
* Fixed a different SQL Injection vulnerability. Hat tip to Lars Wiebusch at Secunia Research for finding this. 

= 0.9 =
* Fixed a SQL Injection vulnerability. Hat tip to Chris Kellum for finding this. 

= 0.8.7 =
* Bug Fix - Fixed a SQL error that inaccurately skipped posts that had votes on multiple days. As a result there should be more accurate database analytics.
* Bug Fix - Fixed bug where [moodthingy] shortcode was only returning the plug-in code at the top of a post/page
* UI - Added a description for the "Automatic Display" option.

= 0.8.6 =
* Added an option to let you completely bypass the plug-in and custom CSS. Useful if you want to edit your CSS from one source or if you are using this plug-in with WordPress Multisite.

= 0.8.5.2 =
* Bug Fix - In the Javascript widget, values now round to the nearest value rather than being truncated.

= 0.8.5.1 =
* Bug Fix - Forgot to comment out reference to localhost :(

= 0.8.5 =
* Added a textarea box to place your extra CSS. This CSS is stored at /uploads/moodthingy-custom.css - every time you update MoodThingy, your CSS should be saved.

= 0.8.4.4 =
* Bug Fix - Removed reference to json2 for IE7 browsers (Special thanks to Aaron Rothrock)
* Added details to the Customization tab about the MoodThingy Mood Rating Widget for WordPress PRO plug-in.

= 0.8.4.3 =
* Bug Fix - Another bug fix for some web servers getting "Parse error: syntax error, unexpected end of file" errors, this time in admin PHP (Special thanks to Aleksandar Petrinic)

= 0.8.4.2 =
* Bug Fix - Possible bug fix for some web servers getting "Parse error: syntax error, unexpected end of file" errors

= 0.8.4.1 =
* Bug Fix - added ended closing PHP tag

= 0.8.4 =
* Added the ability to reset all votes from MoodThingy if you were previously testing and now want to use real data. Be careful with this one!
* Added the ability to toggle sorting in the UI (defaults to on for new installs.)

= 0.8.3 =
* Improved the UI of the Admin dashboard screens.

= 0.8.2 =
* Fixed a bug where we forgot the before_widget and after_widget arguments to the widget section.
* Converted HTML Entities to regular characters when someone wants to tweet the mood they just voted on.

= 0.8.1 = 
* Made a usability change while tweeting replacing #moodthingy to @MoodThingy.

= 0.8 =
* Added functionality to tweet after voting. Publishers can turn off this setting in the Admin menu. 

= 0.7.2 =
* Added shortcode functionality - the shortcode [moodthingy] now adds a MoodThingy widget to a post or a page. That also means that the ability to add a MoodThingy widget to Pages is now possible.
* Fixed a bug where you previously couldn't save the status of a checkbox in the WordPress status.

= 0.7.1 =
* Fixed a bug where new blogs after the 0.7 patch weren't displaying widgets.

= 0.7 =
* Due to various hosting issues for MoodThingy.com, we have temporarily disabled registration at MoodThingy.com and all community features. The centralized website with additional community features will be re-implemented at a later date.

= 0.6.1 =
* Bug fix: Prevent blogs with white text from not being able to see the widget.

= 0.6 =
* Added screenshots for the WordPress Plugin Page.
* Added a widget for themes. Widget can choose the most rated posts in the past day, week, month or year.

= 0.5.4 =
* Bug Fix: Prevent multiple clicks from triggering multiple mood votes.

= 0.5.3 =
* Bug Fix: Added defensibility into CSS to fix layout bugs caused by declaration collisions.
