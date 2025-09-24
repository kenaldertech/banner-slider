=== Banner Slider ===
Contributors: kenaldertech
Author: Kenneth Alvarenga
Author URI: https://kennethalvarenga.com
Tags: slider, carousel, banner, images, responsive
Requires at least: 5.0
Tested up to: 6.8
Stable tag: 1.0
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

== Description ==
Banner Slider is a simple and responsive WordPress plugin that lets you create an image carousel/slider with ease.

- Add images from the WordPress admin using the custom post type "Slides".
- Each slide can have an **optional link URL** and an **optional caption text**.
- Display the slider anywhere with the shortcode `[banner_slider]`.
- Fully responsive design, with auto slide transition and navigation arrows.
- Admin options:
  * Slide transition speed.
  * Maximum banner height.
  * Background color and opacity for the caption text.

== Installation ==
1. Upload the `banner-slider` folder to the `/wp-content/plugins/` directory.
2. Activate the plugin through the “Plugins” menu in WordPress.
3. A new menu item "Slides" will appear in the WordPress admin — add your images there.
4. Insert the shortcode `[banner_slider]` into any page or post where you want the slider to appear.
5. Configure options (speed, height, text background color) under **Settings > Banner Slider**.

== Frequently Asked Questions ==

= Can I have multiple sliders? =
Yes, you can create multiple slides, but the `[banner_slider]` shortcode will display all published slides by default.

= Can I customize the slider design? =
Yes, you can override the CSS in your theme or edit the `assets/slider.css` file.

= Is it mobile-friendly? =
Yes, the slider is fully responsive.

== Screenshots ==
1. Add a new Slide (with image, URL, and text).
2. Example of the slider displayed on the frontend with caption text overlay.
3. Settings page in the WordPress admin.

== Changelog ==
= 1.0 =
* Initial release.
* Custom Post Type "Slides".
* Shortcode `[banner_slider]`.
* Options for speed, height, and caption background color.
* Responsive design with navigation arrows.

== Upgrade Notice ==
= 1.0 =
First release of the Banner Slider plugin.

