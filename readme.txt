=== Oxy Toolbox ===
Contributors: Gagan Goraya, Sridhar Katakam
Tags: oxygen, oxygen builder, oxygen editor
Requires at least: 4.9
Tested up to: 5.4.1
Requires PHP: 5.6
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Adds several useful and time-saving features for the Oxygen builder.

== Description ==

Current Features:

* Functionality of Oxy Undo - adds Undo and Redo buttons; provides autosaving option.
* Functionality of Oxy Class Act - lets you move or copy the styles associated with id or a class of any element to a new class; lets you reset all the styles for the class/id.
* Functionality of Oxy Cleaner - lets you rename classes and remove unused ones.
* Oxy Text Edit - adds a text area to view/edit text of Heading and Text components.
* Back To Top - allows users to smoothly scroll back to the top of the page.
* Editor Tweaks
	* Back To WP Additions - adds Templates and Pages menu items under “Back to WP” menu in the Oxygen editor.
	* Compact View For Element Buttons - makes the buttons for adding elements in the left Add+ panel appear in 3 columns instead of the standard 2.
	* Currently Editing - adds the name of current Template or Page or any other kind of entry that is currently being edited to the left of Structure button in Oxygen’s editor interface.
	* Dropdowns On Hover - makes Media Query, Manage Menu, Back to WP Menu and Select Box dropdowns to appear on hover.
	* Expanded Oxygen Toolbar Menus - makes the buttons for Settings, Stylesheets, Selectors, Admin and Frontend a single click away.
	* Open Back To WP Menu Links In New Tabs - makes links under Back to WP Menu like Admin and Frontend buttons to open in a new tab.
* Oxygen Navigator - adds useful links in the Toolbar for directly editing Pages and Templates with Oxygen; optionally show the toolbar in the Oxygen editor if you want. Makes direct editing of any Template or Page from anywhere literally a single click away.
* Oxygen Rank Math Integration - includes Oxygen editor content in Rank Math's content analsys.
* Oxygen Yoast Integration - includes Oxygen editor content in Yoast's content analsys.
* Oxygen Essentials - enables HTML5 support for elements like the search form and adds some CSS for making essential changes like making all images responsive and fixing the WordPress Toolbar submenu links not clickable issue with sticky header.
* Add a link to go back to the Templates list screen when editing a Oxygen Template.
JS/jQuery Scripts - registers popular scripts like Flickity, Isotope and Infinite Scroll so you can enqueue them anywhere in Oxygen.
* Remove "Themes" and "Theme Editor" menu items from the Appearance menu in the WP admin.

== Installation ==

1. Click on the download link in your purchase confirmation email if you have not already downloaded it after your purchase.

2. Download the plugin's zip file.

3. Go to Plugins > Add New in your WordPress admin. Click "Add New" button, then "Upload Plugin" button, then "Choose File", browse to and select the plugin's zip file.

4. Activate the plugin.

5. Enter the license key and activate your plugin license at Oxygen > Oxy Toolbox > License.

Valid license key should be entered for the plugin to function and to receive automatic updates.

== Changelog ==

= 1.3.1 ( July 17, 2020 ) =
* [Gutenberg] Movied "Disable Gutenberg" as an option under a new "Gutenberg" module and added another option, "Full Width Editor".
* [Back To Top] Fixed Back To Top button not appearing when NextGen Gallery is active.

= 1.3 ( July 14, 2020 ) =
* [Conditions] Fixed Mobile Detect conditions.
* [Navigator] Edit Page, Edit Post and Edit Product admin bar links now appear only on relevant views.
* [Navigator] Fixed frontend links to view the Pages and Posts. All of them were linking to the homepage earlier.

= 1.2.9 ( July 10, 2020 ) =
* [Conditions] Added "Is Affiliate (AffiliateWP)" condition.
* [Navigator] Fixed mis-alignment of panels in the Oxygen editor due to a bug in v1.2.8.

= 1.2.8 ( July 09, 2020 ) =
* Fixed settings export not including the nested options.
* [Table of Contents] Wrapped the button element and div.toc-list in div.oxy-toc in the TOC HTML output.
* [Navigator] Fixed edit post link missing for user roles according to their permissions.
* [Navigator] Changed WP_Query to direct SQL query for the page/posts/templates listings in the WP admin bar for better performance.
* Added function exists checks for oxygen_vsb_register_condition to prevent fatal error when Oxygen is deactivated.
* Added function exists check for is_oxygen_edit_post_locked() to prevent fatal error with older versions of Oxygen.

= 1.2.7 ( June 13, 2020 ) =
* Added the ability to save/export/import plugin's settings.
* Fixed the URL for Isotope script.
* Added Headroom script.
* Updated Splide script.

= 1.2.6 ( June 13, 2020 ) =
* Added a new module: Image Width and Height Size Attributes.

= 1.2.5 ( June 12, 2020 ) =
* Fixed license activation/deactivation issue especially after site has been migrated to a new location.
* Fixed "At least One Product on Sale" condition.

= 1.2.4 ( June 09, 2020 ) =
* Added these WooCommerce conditions:
** Selected Tag has at least One Product
** Selected Category has at least One Product
** At least One Featured Product
** At least One Product on Sale

= 1.2.3 ( June 08, 2020 ) =
* Fixed fatal error on sites where WooCommerce is not active.
* Masked the license key with dots.

= 1.2.2 ( June 07, 2020 ) =
* Fixed Mobile Detect conditions.
* Added WooCommerce conditions. Details: https://oxyplugins.com/doc/conditions/#WooCommerce.
* Added links to OxyExtras' settings page (same and new tab) under Navigator's Oxygen admin bar menu item.

= 1.2.1 ( June 04, 2020 ) =
* Improved Rank Math module to have Rank Math detect images from Oxygen in its XML sitemaps under the Images column.
* Fixed the width of toolbar menu when "Expanded Oxygen Toolbar Menus" editor tweak is enabled.

= 1.2 ( June 01, 2020 ) =
* Removed the visibility of License Key from the plugin's settings page after the plugin has been licensed. Changed the 2-step process of saving + activating/deactivating to a single step.
* Added "Wider Library Flyout Panel" editor tweak.
* Moved Oxygen's "Edit with Oxygen"/"Edit <Template>" to under the Navigator's Oxygen admin bar menu.
* Fixed Collapse Editor button not appearing when editing a Stylesheet.
* Fixed custom TOC title not appearing.
* Fixed the CSS of "Expanded Oxygen Toolbar Menus" in preparation for Oxygen 3.4.
* Removed the "Remove default padding, default margin and list styles on ul, ol elements with a class attribute" CSS code in Essentials.

= 1.1.9 ( May 27, 2020 ) =
* Major overhaul of Navigator module
** added support for editing and viewing Pages and Posts.
** added links to open in new tab for Templates and Pages.
** added "Show ACF Field Groups" option.
** added "Show Fluent Forms' Forms" option.
** added "Show WooCommerce Products" option.
** added "New" Admin Bar Menu Additions option which adds links to new ACF Field Group, Code Snippet, Fluent Forms form, Reusable under "New" menu item.

= 1.1.8 ( May 24, 2020 ) =
* Improved Rank Math module to include the parent Oxygen Template (if a Template has been selected in the RENDER PAGE USING TEMPLATE dropdown) in Rank Math's content analysis.
* Fixed media query buttons appearing vertically on hover when Dropdowns On Hover option is enabled.
* Added blue underline for the active media query button when Dropdowns On Hover option is enabled.
* Replaced system font with Source Sans Pro in Offline Mode module.
* Changed display of label from inline-block to inline in the Essentials module.

= 1.1.7 ( May 23, 2020 ) =
* Fixed remove media styles button not being easily clickable when "Media Query Buttons" editor tweak is enabled.

= 1.1.6 ( May 23, 2020 ) =
* Added "Offline Mode" module. Credit: Supa Mike and David Browne.
* Added "Media Query Buttons" editor tweak. Credit: Yan Fodé Kiara.
* Added "CSS Tweaks" editor tweak.
* Added "Remove min-width and min-height for empty Divs" editor tweak.
* Added Splide script.
* Changed display of label to inline-block from block in Essentials.

= 1.1.5 ( May 18, 2020 ) =
* Added Body Class condition.
* Added Browser Detect condition.
* Made the Text Edit module's textarea resizable with a min-height of 15vh.
* Added != operator for the "Author has CPT entry" condition.

= 1.1.4 ( May 16, 2020 ) =
* Fixed an issue with adding library elements in the Undo module.

= 1.1.3 ( May 15, 2020 ) =
* Added the following Conditions:
** Archive Type
** MemberPress Membership
** RCP Membership
** Referrer URL Parameter
** Language
* Fixed undefined index notice issue introduced from the recently added success message upon saving plugin's settings.

= 1.1.2 ( May 13, 2020 ) =
* Added Conditions module with several conditions. More to follow.

= 1.1.1 ( May 12, 2020 ) =
* Added an option to disable keyboard shortcuts in the Undo module.
* Added "Oxy Toolbox settings have been saved." success message after pressing the Save Changes button on the plugin's settings page.

= 1.1 ( May 11, 2020 ) =
* Disabled undo and redo in the class name fields and fixed error upon undoing/redoing after adding a class name.

= 1.0.9 ( May 11, 2020 ) =
* Added Disable Gutenberg module.

= 1.0.8 ( May 10, 2020 ) =
* Added Table of Contents module.
* Added a link to the Feature requests Trello board in the plugin's settings page.

= 1.0.7 ( May 08, 2020 ) =
* Added Reading Progress Bar module.
* Excluded styling of lists in Gutenberg from being reset. Thanks Yan Fodé Kiara.
* Fixed styling in Navigator module to make the ruler in Oxygen editor visible again.
* Added links to changelog, Facebook group and Support on the plugin's settings page.

= 1.0.6 - May 07, 2020 =
* Fixed the size of Oxygen icons appearing larger than they should be in the WP Toolbar on admin pages when certain plugins like Gravity Forms/MailPoet and Navigator are enabled.
* Fixed Repeater components vanishing on clearing styles with Class Act module.
* Removed antialiased font smoothing for body tag from the Essentials module. Ref.: https://usabilitypost.com/2012/11/05/stop-fixing-font-smoothing/, https://responsivedesign.is/articles/font-smoothing/.
* Removed "text-rendering: optimizeSpeed" for body tag from the Essentials module. Ref.: https://bocoup.com/blog/text-rendering.

= 1.0.5 - May 05, 2020 =
* Added link to the settings page in the plugins list admin page.
* Replaced base64 string for Oxygen icons with png in the WP Toolbar when Navigator is enabled.

= 1.0.4 - May 05, 2020 =
* Added a new module: Open External Links In A New Tab
* Fixed undefined variable PHP notices.
* Got rid of CSS for removing all animations and transitions for people that prefer not to see them via prefers-reduced-motion. This is apparently causing issues with Animate on Scroll and other needed animations.

= 1.0.3 - May 04, 2020 =
* Fixed Templates and Pages links under Back To WP Additions not linking to the correct URLs for sites on subdomains.
* Fixed items in the Previewing dropdown not being reachable on hover with "Dropdowns On Hover" enabled.

= 1.0.2 - May 04, 2020 =
* Fixed unwanted space at the top coming from enabling WP Toolbar in the Oxygen editor via Navigator module.
* Fixed back to top button not being clickable reliably in the Oxygen editor.

= 1.0.1 - May 03, 2020 =
* License check deactivation to make the plugin work temporarily.

= 1.0 - May 03, 2020 =
* Initial Release.
