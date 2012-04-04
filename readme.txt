=== Plugin Name ===
Contributors: clarklab
Donate Link: http://clarklab.com/
Tags: twitter, tweet, make_clickable, regex
Requires at least: 2.7
Tested up to: 3.3.1
Stable tag: trunk

A plugin for converting @user metions, #hashtags and URLs in a tweet into clickable links.

== Description ==

In a recent project, I had a bunch of tweet content saved and needed a way to convert all URLs, hashtags, and user mentions contained within into clickable links. WordPress has a built-in function called [make_clickable()](http://codex.wordpress.org/Function_Reference/make_clickable), so I took it an extra step to make_clickable_tweet(). It’s basically a fancy regular expression, but I figured someone else out there might need it.

== Installation ==

Using the plugin is pretty dang simple, as the function only has one parameter, the content you wanted returned in a clickable form. To use the plugin, simply activate it then start using the function in your templates like so:

`<?php make_clickable_tweet($tweetcontent); ?>`

Of course, that above function will simply return the tweet content, if you'd like to display it you might want to toss an echo in front of there.

== Frequently Asked Questions ==

= Why did you make this? =

I had a bunch of tweet data that I needed to render like a real tweet.

== Screenshots ==

None yet

== Changelog ==

= 0.2 =

Changed order of regular expressions.

= 0.1 =

Release

== Upgrade notice ==

None yet