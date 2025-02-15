=== VisualWeb lazy load ===
Contributors: fiverrpelfed
Donate link: https://visualweb.co.uk/lazyload 
Tags: lazy load, image lazyload, image load, selective lazy load
Requires at least: 3.3
Tested up to: 5.1.0
Stable tag: trunk
Requires PHP: 5.2.4
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-3.0.en.html

Reduce the loading time while opening your wordpress website, accelerate opening time. Images outside of viewport (visible part of web page) wont be loaded before user scrolls to them.

== Description ==

VisualWeb lazy load plugin's aim is to speed up your website powered by WordPress.
This will prove helpful for getting a good score on GTmetrix, YSlow and Pingdom.
It delays loading of selected images in (long) web pages. 
Images outside of viewport (visible part of web page) wont be loaded before user scrolls to them.
Unlike other plugins of similar type, this plugin allows you to choose which images are applied to it via the css selector(s).

After activating the plugin, when the website is viewed, the text will be loaded first and then the images. 
This will help reduce the loading time, the images will load later based on user screen scrolling by jQuery script. 
Scrolling down, more image will be loaded, no need to call an external server.

Wish to reduce page loading time significantly and selectively? Then choose it.

<strong>Features:</strong>
<ul>
<li>Truly reduce server side loading time.</li>
<li>Able to turn lazy load on or off</li>
<li>Able to choose which image elements are lazy loaded</li>
</ul>

== Installation ==

1. Upload folder 'visualweb-lazy-load' to the '/wp-content/plugins/' directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. After activation, you can configure settings from the menu -> Lazy Load

== Frequently asked questions ==

Q: Where are the images going?<br />
A: Still in your website, they will load on demand.

Q: What should I do after activation.<br />
A: Take a look in the setting menu.

== Screenshots ==

1. Admin Section

== Changelog ==

= 1.0.6 =
* fixed issue with lazy load affecting WP admin area
= 1.0.5 =
* fixed issue with incorrect selector
= 1.0.4 =
* Added in 'sizes' to the code
= 1.0.3 =
* Tidy up the code
= 1.0.2 =
* Changes to Plugin Description
= 1.0.1 =
* Changes to JS to make names unique, avoiding possible conflicts with similar functions.
= 1.0.0 =
* Initial release.


== Upgrade Notice ==