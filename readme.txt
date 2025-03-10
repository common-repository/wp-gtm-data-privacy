=== Cookie Dash ===
Contributors: tnhsaesop
Tags: Google Tag Manager, Tag Manager, GDPR, CCPA, Data Privacy
Requires at least: 5.2
Tested up to: 5.9
Stable tag: 1.2.3
Requires PHP: 7.2
License: GPL v2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

A plugin for quickly deploying Google Tag Manager on WordPress, with a cookie consent popup that disables the container if consent is declined.

== Description ==
Cookie Dash is a plugin meant to help people deploy Google Tag manager on their WordPress websites in a broad data privacy compliant manner. 

Privacy law is complex and there are many more granular solutions for controlling the specific output of tags and managing consent.  For people who like to keep things simple we\'ve taken a different approach with this plugin.  A basic cookie consent collection popup is included with the plugin, and if consent is denied, the plugin will disable the outputting of the Google Tag manager scripts to the page.  

This plugin works under the assumption that all marketing tags for 3rd party tools that collect personal information are deployed through Google Tag Manager.

== Installation ==
1 Download the plugin
2 Upload the plugin zip file to your plugins directory 
3 Activate the plugin from your plugin page
4 Go to Settings > Cookie Dash
5 Fill out the form fields in the settings screen
6 Test your container output by using Google Tag Assistant https://chrome.google.com/webstore/detail/tag-assistant-by-google/kejbdjndbnbjgmefkgdddjlbokphdefk?hl=en

== Changelog ==

Version 1.0

Initital release with basic cookie consent that blocks the load of the Google Tag manager container when users decline personalization cookie consent.  

Version 1.1

- Added the ability to set a list of allowed domains that the GTM container can be output on
- Added the ability to choose the privacy policy slug 
- Added opt-in vs opt-out support for GDPR compliance and other opt-in based privacy laws
- Added admin notification when plugin is not configured

Version 1.1.1

- Bug fix

Version 1.2

- Rebranded to Cookie Dash
- Added opt-in and opt-out support for sites with GDPR compliance needs (and other opt-in based laws)
- Removed manual privacy policy URL slugs, plugin now pulls privacy policy URL from WordPress using a native WordPress hook

Version 1.2.1

- Bug fixes

Version 1.2.2

- Added bug fix causing favicons not to load

Version 1.2.3

- Minified js for SEO

