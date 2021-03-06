=== Google Places Reviews ===
Contributors: impressorg, dlocc, webdevmattcrom, shawnhooper
Donate link: https://wpbusinessreviews.com/
Tags: google, reviews, google reviews, google places, google places reviews, testimonials, google review widget, google business reviews, google review, review, google place review, google map reviews, google reviews pro, facebook reviews, facebook page reviews, yelp reviews, yelp business reviews
Requires at least: 4.2
Tested up to: 5.3
Stable tag: 1.5.2
License: GPL2

Display Google Places Reviews on your WordPress website and help boost consumer confidence and search engine optimization.

== Description ==

Easily display Google Reviews on your WordPress website using a powerful and intuitive widget. Great for restaurants, retail stores, franchisees, real estate firms, hotels and hospitality, and nearly any business with a website and reviews on Google.

= Why Use this Plugin? =

This plugin allows you to display Google reviews on your WordPress website. Why is this important? Positive reviews on websites like Google help businesses gain additional exposure and further enhance their online credibility. As well, positive reviews add substantial credibility to any business and can lead to increased conversion rates and sales.

= Plugin Features =

* Google Business Reviews - Display up to 3 business reviews per location.
* Detailed Business Information - Show the business name, website, Google+ page and more.
* Versatile Widget Themes - Choose from a selection of stunning widget themes that fit light and dark color schemes that make integration with your website design effortless.
* Google Places Autocomplete - Easily lookup businesses in your area through the widget interface using the power of Google search.
* Actively Supported and Developed - We are a team of expert developers based in San Diego, California and we stand by our work. Got a problem? Hit us up.

There is significant data that shows how much consumers care about online reviews but very little information about what businesses are doing to respond to this phenomenon. How about displaying reviews on your WordPress website from Google?

Google Places Reviews allows you to display up to 3 business reviews with the free version and 5 with the Pro version. Setup is quick and easy. Simply install the plugin, insert your Google API (free and documented), and drag the widget into any sidebar to configure the options.

= WP Business Reviews =

*WP Business Reviews* is a **significant upgrade** to *Google Places Reviews* that adds many features that will allow you to further customize how you display reviews on your WordPress website.

[Upgrade to WP Business Reviews](https://wpbusinessreviews.com "Upgrade to WP Business Reviews")

[youtube https://www.youtube.com/watch?v=3xNJX5cjdQ0]

== Installation ==

**Automatic Install:**

1. Log into your WP-Admin
2. Navigate to 'Plugins' > 'Add New'
3. Search for "Google Places Reviews" and install it from there.

**Manual Install:**

1. Upload the `google-places-reviews` folder and it's contents to the `/wp-content/plugins/` directory or install via the WP plugins panel in your WordPress admin dashboard
2. Activate the plugin through the 'Plugins' menu in WordPress
3. That's it! You should now be able to use the widget.

== Frequently Asked Questions ==

= How do I obtain a Google Places API key? =

In order for the plugin to access your Google reviews, you must have a valid Google Places API key with the Google Places API and Google Maps API enabled. To get started, please review [how to create a Google Places API key](https://wpbusinessreviews.com/documentation/platforms/google/).

= Why does the widget look funny in my theme? =

Most likely your theme has conflicting CSS that is interfering with the themes included with the plugin. If you're handy with CSS this can be an easy fix. If you are new to CSS then try out the Bare Bones theme to see if that looks nicer.

= Are style (CSS) and/or theme compatibility issues supported? =

We do our best to support users of the free version of the plugin. [WP Business Reviews](https://wpbusinessreviews.com "Upgrade to WP Business Reviews") is where customers receive priority support. If you are experiencing a style issue and need help, post in the WordPress.org support forum and we will do our best to get it set up nicely for your theme.

= Are there prebuilt styles included in the plugin? =

Yes, there are three basic themes included in the free version of the plugin.

== Screenshots ==

1. An admin view of the widget in a WordPress sidebar

2. Minimal widget themes displayed on the demo site

3. Shadow widget themes displayed on the demo site

4. Inset widget themes displayed on the demo site

5. The plugins settings page found under Settings > Google Reviews

== Changelog ==

= 1.5.2: October 28th, 2019 =
* Maintenance: Reviewed plugin compatibility with WordPress 5.3 for compatibility and updated the plugin tested up to version.

= 1.5.1: May 16th, 2019 =
* Maintenance: Reviewed plugin compatibility with WordPress 5.2 for compatibility and updated the plugin tested up to version.

= 1.5.0 =
* We have recently launched a new premium plugin for reviews called [WP Business Reviews](https://wpbusinessreviews.com/?plugin=google-places-reviews). You can use this new WordPress review plugin to display your best reviews from platforms like Google, Yelp, and Facebook right on your website.
* New: Implemented webpack and SASS for the styles.
* Tweak: Modified upsells for new WP Business Reviews plugin.

= 1.4.3 =
* New: Scripts and styles are now enqueued conditionally so that they are only loaded when the widget or shortcode is used.
* Fix: Reviewers with actual avatars appearing incorrectly as the default placeholder icon.
* Fix: Character Limit setting applied to all widgets on the page instead of individually.
* Tweak: Various JS fixes and code cleanup.
* Tweak: CSS compatibility with TwentySeventeen.

= 1.4.2 =
* Fix: Enqueue Maps JS due to new Google API Key requirement
* Tweak: Display warning message when an Google API error is detected to help prevent confusion

= 1.4.1 =
* Solidify Cache expiration setting for stability
* Store Place Avatar as Data URI to avoid additional API calls
* Wrap default image in url() correctly

= 1.4 =
* New: Improved widget UI when viewing under Appearances > Widget
* New: Updated Google logo through out plugin
* Tweak: CSS tweaks for better frontend theme compatibility
* Tweak: Gulp now used to compile POT file for translation usage
* Tweak: Text domain changed back to 'google-places-reviews' do that the plugin can be included for translation by WordPress.org polyglots
* Fix: z-index conflict with Custom Sidebars plugin by WPMUDev
* Fix: Error returned from google when API url contained malformed characters - now we sanitize the URL before passing it to Google's API; this will help businesses with unconventional characters in their name connect to Google's API
* Fix: Prevent conflict with other review bundle plugins' clear cache feature by prefixing ajax callback

= 1.3 =
* Added compatibility with Siteorigin's PageBuilder
* Added compatibility with WordPress Customizer
* Added compatibility with WPMUDEV's Custom Sidebar's plugin

= 1.2.1 =
* Fix: Broken avatar images displayed for some reviews where the user had not set an avatar

= 1.2 =
* New: Language .pot file for translators
* New: Added additional widget field tooltips
* New: Place "Type" filter to help users find their locations' Place ID on Google
* Update: Switched from Google Places API "Reference" to "Place ID"
* Update: Textdomain changed from 'google-places-reviews' to a much more manageable 'gpr'
* Update: Better tooltip output using new gpr_admin_tooltip function
* Update: Removed usage of GPR_DEBUG in favor of SCRIPT_DEBUG constant
* Fix: "Clear Cache" button under Advanced Options now actually clears the cache
* Fix: Several minor PHP warnings and notices
* Fix: UX improvement: "Hide Google Logo" label wasn't click-able to select checkbox, now it is
* Fix: Minor admin CSS touch ups for WP 4.2

= 1.1.3 =
* Modified text in activation banners so it's more informative & relevant to the free version

= 1.1.2 =
* Added activation banner
* Updated readme.txt
* Fully I18n (internationalization) ready

= 1.1.1 =
* Fix: "Disable Title Output" under the "Advanced Options" in the widget wasn't working, it is now; thanks "game writer" for notifying us of this bug.
* Fix: Avatar image overlapping into the content because of lack of max-width CSS property.

= 1.1.0 =
* New: Plugin thumbnail that now appears in WP repo search
* Improvement: If an error occurs the widget will output them and then ensure that the bad result is not cached so if the user fixes the error they won't have to manually clear the cache.
* Minor improvements the the widget's frontend appearance
* Fixed bad links to plugin docs
* Tested WP 4.0 functionality to approve bumping version compatibility

= 1.0.1 =
* Update: Removed schema.org tags from the free version of the plugin.
* Update: Fixed minor CSS issues with star counts collapsing below review avatar for some sidebars with tight widths; several padding reductions to support slimmer widths.

= 1.0 =
* Initial Free version release!
