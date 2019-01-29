=== Gravity Forms Pre-Submission Confirmation Plugin ===
Contributors: mmedia
Donate link: https://mathisonmedia.com
Tags: form, gravity forms, presubmission, confirmation
Requires at least: 3.6
Tested up to: 4.9.8
Stable tag: 1.0.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Adds support for pre-submission confirmation to Gravity Forms before form is submitted.

== Description ==

This plugin adds support to add a pre-submission confirmation page to the end of your Gravity Forms by using merge tags in an HTML field.

== Installation ==

1. Download and unzip the plugin.
2. Upload `gravityforms-presubmission` to the `/wp-content/plugins/` directory.
3. Activate the plugin through the 'Plugins' menu in Wordpress.

== Configuration ==

1. With the plugin activated, open the Gravity Forms form you wish to add the presubmission confirmation to.
2. Add a Page Break field type to the form to create a new page.
3. Next, add a HTML field. Rename the HTML field to 'Confirmation'.
4. Select the HTML field to show the content area.
5. Add any merge tags you'd like to display.

== Examples ==

All merge tags can be found on [GravityFormsHelp](https://docs.gravityforms.com/merge-tags/).
Here is how to type the merge fields into the HTML content area:
{Name (First):4}, {Question:5}