=== WPSSO Product Metadata (GTIN, UPC, EAN, ISBN, MPN) for WooCommerce ===
Plugin Name: WPSSO Product Metadata for WooCommerce
Plugin Slug: wpsso-wc-metadata
Text Domain: wpsso-wc-metadata
Domain Path: /languages
License: GPLv3
License URI: https://www.gnu.org/licenses/gpl.txt
Assets URI: https://surniaulula.github.io/wpsso-wc-metadata/assets/
Tags: woocommerce, gtin, upc, ean, isbn, mpn, custom fields, global identifier, manufacturer part number, attribute, information, product
Contributors: jsmoriss
Requires PHP: 5.6
Requires At Least: 4.4
Tested Up To: 5.6
WC Tested Up To: 4.7.1
Stable Tag: 1.6.1

GTIN, GTIN-8, GTIN-12 (UPC), GTIN-13 (EAN), GTIN-14, ISBN, MPN, depth, and volume for WooCommerce products and variations.

== Description ==

<p style="margin:0;"><img class="readme-icon" src="https://surniaulula.github.io/wpsso-wc-metadata/assets/icon-256x256.png"></p>

Easily include additional metadata fields in the WooCommerce **Product data** metabox and the purchase page **Additional information** section:

* GTIN
* GTIN-8
* GTIN-12 (UPC)
* GTIN-13 (EAN)
* GTIN-14
* ISBN
* MPN (Manufacturer Part Number)
* Depth
* Volume

The information shown under the WooCommerce purchase page **Additional information** section changes as different variations are selected (or unselected).

The *SSO &gt; WooCommerce Metadata* settings page allows you to enable or disable product metadata with a simple checkbox, along with customizing the label and placeholder for different languages (aka WordPress locales).

The product metadata fields are integrated seamlessly in the WooCommerce product editing page, for both simple products and product variations.

Product global identifier values (ie. GTIN, GTIN-8, GTIN-12, GTIN-13, GTIN-14, ISBN, and MPN) are also searchable from the front-end and the WooCommerce Products admin page.

**Provides Schema (aka Schema.org) mpn, gtin14, gtin13, gtin12, gtin8, gtin, productID isbn, depth, and additionalProperty fluid_volume properties to the [Schema JSON-LD Markup add-on](https://wordpress.org/plugins/wpsso-schema-json-ld/) for Google Rich Results, Rich Snippets, and Structured Data.**

<h3>Can You Add More Product Metadata Fields?</h3>

Absolutely. Assuming the information can be included in a [Schema Product property value](https://schema.org/Product), [create a new topic in the plugin support forum](https://wordpress.org/support/plugin/wpsso-wc-metadata/) with the details (including the suggested Schema property name) and we'll have a look. ;-)

<h3>Includes WooCommerce Fluid Volume Units</h3>

The WPSSO Product Metadata for WooCommerce add-on also includes a **Fluid volume unit** option in the *WooCommerce &gt; Settings &gt; Products* settings page:

* ml
* cl
* l
* kl
* US tsp
* US tbsp
* US fl oz
* US cup
* US pt
* US qt
* US gal

<h3>Includes Meta Tags and Schema Markup</h3>

The [WPSSO Core plugin](https://wordpress.org/plugins/wpsso/) will automatically include the following Open Graph product meta tags for enabled product metadata:

* product:ean
* product:isbn
* product:mfr_part_no
* product:upc

The [Schema JSON-LD Markup add-on](https://wordpress.org/plugins/wpsso-schema-json-ld/) will automatically include the following Schema Product and Offer properties for enabled product metadata:

* mpn
* gtin14
* gtin13
* gtin12
* gtin8
* gtin
* productID isbn
* depth
* additionalProperty fluid_volume

<h3>WPSSO Core Plugin Required</h3>

WPSSO Product Metadata for WooCommerce (aka WPSSO WCMD) is an add-on for the [WPSSO Core plugin](https://wordpress.org/plugins/wpsso/).

WPSSO Core and its add-ons make sure your content looks best on social sites and in search results, no matter how your webpages are shared, re-shared, messaged, posted, embedded, or crawled.

== Installation ==

<h3 class="top">Install and Uninstall</h3>

* [Install the WPSSO Product Metadata for WooCommerce add-on](https://wpsso.com/docs/plugins/wpsso-wc-metadata/installation/install-the-plugin/).
* [Uninstall the WPSSO Product Metadata for WooCommerce add-on](https://wpsso.com/docs/plugins/wpsso-wc-metadata/installation/uninstall-the-plugin/).

== Frequently Asked Questions ==

<h3 class="top">Frequently Asked Questions</h3>

* None.

== Screenshots ==

01. Information shown under the "Additional information" section changes as different variations are selected.
02. Enabled product metadata fields are added seamlessly under the product inventory tab.
03. Enabled depth and volume metadata fields are added seamlessly under the product shipping tab.
04. Enabled product metadata fields are added seamlessly under the product variations tab.

== Changelog ==

<h3 class="top">Version Numbering</h3>

Version components: `{major}.{minor}.{bugfix}[-{stage}.{level}]`

* {major} = Major structural code changes / re-writes or incompatible API changes.
* {minor} = New functionality was added or improved in a backwards-compatible manner.
* {bugfix} = Backwards-compatible bug fixes or small improvements.
* {stage}.{level} = Pre-production release: dev < a (alpha) < b (beta) < rc (release candidate).

<h3>Standard Version Repositories</h3>

* [GitHub](https://surniaulula.github.io/wpsso-wc-metadata/)
* [WordPress.org](https://plugins.trac.wordpress.org/browser/wpsso-wc-metadata/)

<h3>Changelog / Release Notes</h3>

**Version 1.7.0 (2020/11/29)**

* **New Features**
	* None.
* **Improvements**
	* Updated information and help messages in the SSO &gt; WooCommerce Metadata settings page.
* **Bugfixes**
	* None.
* **Developer Notes**
	* None.
* **Requires At Least**
	* PHP v5.6.
	* WordPress v4.4.
	* WPSSO Core v8.14.0.
	* WooCommerce v3.6.4.

**Version 1.6.1 (2020/10/17)**

* **New Features**
	* None.
* **Improvements**
	* Refactored the add-on class to extend a new WpssoAddOn abstract class.
* **Bugfixes**
	* Fixed backwards compatibility with older 'init_objects' and 'init_plugin' action arguments.
* **Developer Notes**
	* Added a new WpssoAddOn class in lib/abstracts/add-on.php.
	* Added a new SucomAddOn class in lib/abstracts/com/add-on.php.
* **Requires At Least**
	* PHP v5.6.
	* WordPress v4.4.
	* WPSSO Core v8.13.0.
	* WooCommerce v3.6.4.

== Upgrade Notice ==

= 1.7.0 =

(2020/11/29) Updated information and help messages in the SSO &gt; WooCommerce Metadata settings page.

= 1.6.1 =

(2020/10/17) Refactored the add-on class to extend a new WpssoAddOn abstract class.

