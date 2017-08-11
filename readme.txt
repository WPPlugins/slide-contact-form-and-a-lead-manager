=== Plugin Name ===
Contributors: lior izik
Donate link: http://www.image-psd-to-wordpress.com
Tags: leads, contact slider, contact
Requires at least: 2.8
Tested up to: 2.8.5
Stable tag: 2.0 (beta)

Integrate a Sliding Contact Us bar on the left side of the Site

== Description ==
This is a cool and functional contact form that integrates with an easy to use leads system.
The main purpose of this plugin is to have a visible Contact us button on the left side of the screen so users can contact you easily.

All the contacts being kept in the leads system and can be managed from the time you get a new lead, until you get the deal and close it.

This plugin can be easily integrated with Google Adwards and leads from the site, can be shown in the Adwards system so you can check your conversion ratio.

The plugin contact fields can be easily changed by the admin.

The admin can choose what response will be sent to the user after sending the contact form and if he like him to be redirected to a thank you page or just get a simple thank you message.

== Installation ==

1. Upload `slide-contact-form-and-a-lead-manager` folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Use [leadsform] shortcode  to get a contact us form in post or pages.

== Frequently Asked Questions ==

= I have activated the plugin, but it seems not working? =

Requires wp_head() and get_footer() function to be called in the template file. This is the only requirement for the plugin to work.

== Screenshots ==
1. Easily configarable form. Add an field and press update. You're done.
2. You can easily manage your Leads in this page. You can also edit or delete a lead if you wish.
3. After installing the plugin you'll get a sliding contact us form on the left side of the site.

== Changelog ==

= 2.0 (beta) =
* Solved all the problems that user experienced with version 1.4 and added few features on user request
* Multiple email option added. [Now admin can set multiple email addresses to receive contact us information]
* Captha Script added.
* Frontend form customization options added.
* More improved and dynamic frontend this time.

= 1.4 =
* shortcode added. Use [leadsform] to any page and get a contact us form now.

= 1.3 =
* Auto responder added. [if user provide an email address and auto responder is on, user will receive an auto-generated message]
* Thank you messaage method added [simple & advanced]
* Google Lead Conversion js added.
* Corrected a minor bug. [in admin lead-list page the data of sent column was showing incorrectly.]



= 1.2 =
* fixed a major bug in js [user can't mail 2nd time if the first time mail was suessful adn page isn't refreshed]
* New Feature:All mails sent through the system stores in a db table. Admin can set status to those mails.
* html tags are allowed in the "Thank You" and "Error" message.


= 1.1 =
* removed ie6PngFix.js
* replace all .png images with .gif

