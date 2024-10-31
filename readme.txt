=== Punchlist ===
Contributors: plnic
Tags: punchlist, collaboration, feedback, annotation, tools, design
Requires at least: 5.5
Tested up to: 6.5
Stable tag: 1.5.2
Requires PHP: 7.4
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

== Description ==

This plugin will allow you to share your posts and pages (including drafts!) for collaboration on Punchlist.

### 🥊 The #1 Creative Collaboration & Feedback Management Platform for WordPress

Easily share website drafts without having clients log in to your WordPress account with [Punchlist’s WordPress plugin](https://punchlist.com/wordpress-integration?_gl=1*i7tyon*_gcl_au*NDQxNjEyNTYzLjE3MTE2MzI1MjE.*_ga*MTA1OTUwOTQzNi4xNzExNjMyNTIx*_ga_4L522ZFHFC*MTcxNDc1OTIxNS4yMS4xLjE3MTQ3NTk2MDYuNDYuMC4w). 

Whether you are a website developer, project manager, web designer, or someone who uses WordPress regularly, this plugin can help you save time when gathering feedback and collaborating on projects.

### 🥊 About

This WordPress plugin is a companion to the Punchlist application. With it, you can
- Create new projects and add new pages to existing projects without leaving the WordPress admin dashboard
- Develop website draft previews that are hidden from the public but available via Punchlist
- Collaborate with clients and peers without the need to issue WordPress user accounts

### 🥊 How it works

*Starting a New Project*

1. Install the Punchlist for WordPress plugin 
2. Open your post or page editor in WordPress
3. Go to the right-side navigation in WordPress
4. Scroll down to the section that says “Punchlist”
5. Click “start a new Punchlist Project”
6. Click the link that appears that says “Go To Punchlist Project”
7. Congratulations! You can now view the WordPress draft in Punchlist. Use the share button at the top right to send clients and team members the Punchlist page with your WordPress website draft.


*Adding to an Existing Project*

1. Install the Punchlist for WordPress plugin 
2. Open your post or page editor in WordPress
3. Go to the right-side navigation in WordPress
4. Scroll down to the section that says “Punchlist”
5. Click the “Add to Existing Project” dropdown
6. Choose which Project you want to add this website draft to
7. Click the button below that says “Add to Project NAME”
8. Click the button that says “Go to Punchlist Project”
9. Congratulations! Your website draft is in the project you assigned it to. Use the share button at the top right to send clients and team members the Punchlist page with your WordPress website draft.

To access this plugin, you will need a Punchlist account.

### 🥊 How to Acquire an API Key & Install the Plugin
1. [Create a Punchlist account](https://app.punchlist.com/register/freetrial?_gl=1%2A9hb1k5%2A_gcl_au%2AODg5MDM5NTkuMTcxMjgzNjExMg..%2A_ga%2AMTU1MDc5NjI1Mi4xNzA0OTE3MzI2%2A_ga_4L522ZFHFC%2AMTcxNDY1NzM0OC4xMzIuMS4xNzE0NjU5ODE4LjU4LjAuMA)
2. On the Punchlist app, click your profile in the top right corner and select “API Tokens” from the dropdown OR head here
3. Give your API token a name
4. Copy the Access Token from the pop-up window
5. Go back to WordPress. Click the Punchlist item on your WordPress sidebar
6. Paste the Access Token into the field next to the button that says “Verify API Integration”
7. Click the “Verify API Integration” Button
8. Once that’s done, you can start using the Punchlist integration for WordPress!

### 🥊 Leave Us Feedback

At Punchlist, we are always looking for ways to improve. Please leave us any feedback, bug reports, or further feature requests you’d like to see by contacting us [here](https://punchlist.com/contact-us#hs-chat-open).

== Changelog ==
= 1.5.2 =
Update README contact and copy

= 1.5.1 =
Update README and usage instructions 

= 1.5.0 =
* Tidy up security issues

= 1.4.5 =
* Re-launching the plugin, tested up to 6.5

= 1.4.4 =
* Moves remote Punchlist script to the footer
* Updated installation instructions

= 1.4.0 =
* Prevents unnecessary warning

= 1.3.8 =
* Version bump

= 1.3.7 =
* Re-enables PHP 7.4 compatibility. 

= 1.3.6 =
* Fixed client error preventing retrieval of current projects

= 1.3.4 =
* Version bump

= 1.3.2 =
* URL fix

= 1.3.0 =
* Re-implements draft preview to work with the recently release Punchlist 2.0.

= 1.2.8 =
* Rolled back incorrect PHP version requirement

= 1.2.6 =
* Updated all dependecies to their latest version.
* Updates API endpoints.

= 1.2.5 =
* Fixes a bug which prevented retrieving name title in WP 5.9
* Updated all dependecies to their latest version.

= 1.2.4 =
* Updated domains to match Punchlist's infrastructure changes
* Updated all dependecies to their latest versions.

= 1.2.3 =
* Removed pre-populated field value from PL API key

= 1.2.2 =
* Corrected version mismatch in code vs README.

= 1.2.1 =
* Updated method names to avoid collisions.

= 1.2 =
* Added basic and sane security measures based on WP reviewer recommendations (thanks and sorry for sending it up half baked)
* Updates the API library to sanitize all third party responses
* No new functionality added

= 1.1 =
* Added support for adding pages to existing projects.

= 1.0 =
* Provides the ability to create projects from the edit screen.

== Upgrade Notice == 
= 1.2.8 =
* Updated API calls.

= 1.2.5 =
* Previous versions of this plugin won't be able to create a new Punchlist project in WP 5.9+
* Adding pages to existing projects would still work but it's recommened to update for full functionality

= 1.2.4 = 
* Fixes issues with API communication to the Punchlist application.

= 1.2.3 =
* The removal of the value removes a possible unescaped value from being echo'd.

= 1.2.2 =
* Avoid a version mismatch.

= 1.2.1 =
* Prevents possible conflicts with other third party code.

== Screenshots ==

1. Admin page
2. Editor