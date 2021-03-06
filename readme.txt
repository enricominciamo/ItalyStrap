=== ItalyStrap ===
Contributors: overclokk
Donate link: http://www.italystrap.it/
Tags: breadcrumbs, breadcrumb, seo, performance, schema.org, rich snippet, bootstrap, twitter bootstrap, css, responsive-layout, custom-menu, editor-style, featured-images, flexible-header, post-formats, sticky-post, translation-ready, blog, design, journal, lifestream, tumblelog, bright, clean, colorful, geometric, modern, playful, simple, whimsical, vibrant
Requires at least: 3.8
Tested up to: 4.1
Stable tag: 2.1.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Make your web site more powerfull.

== Description ==

**[ItalyStrap Theme](http://www.italystrap.it/)** will add powerful features to your WordPRess site.

ItalyStrap is a Wordpress starter theme based on [HTML5 Boilerplate](http://html5boilerplate.com/), [Bootstrap](http://getbootstrap.com/), [Schema.org](http://schema.org/), [Open Graph](https://developers.facebook.com/docs/opengraph/), [Twitter cards](https://dev.twitter.com/docs/cards)

[![Built with Grunt](https://cdn.gruntjs.com/builtwith.png)](http://gruntjs.com/)

**Features include:**

* HTML5 Bolierplate
* CSS3
* Twitter Bootstrap 3
* Schema.org
* Facebook opengraph
* Twitter cards
* **Breadcrumbs.**
* SEO Friendly (che vuol dire tutto e niente :-))
* WPO Friendly ;-)
* E chi più ne ha più ne metta :-P

== Installation ==

Clone the git repo

```git clone git://github.com/overclokk/ItalyStrap.git```

or [download it](https://github.com/overclokk/ItalyStrap/releases/latest) unzip and place it in your folder themes (/wp-content/themes/) directory, rename folder to ItalyStrap and activate it via Admin - Appearance - Themes

Then [download Italystrap Child Theme](https://github.com/overclokk/ItalyStrap-child/archive/master.zip) and use it for your customizations

If you want to keep it updated please also install github-updater from your admin dashboard and use the child theme for your customizations.


== Frequently Asked Questions ==


== Screenshots ==


== Changelog ==

= 2.1.0 =
Release Date:

(Dev time 50h)

* Add dev time
* Add ITALYSTRAP_THEME constant for internal use
* Fix for deprecated function WordPress SEO by Yoast
* Add external loop files for DRY don't repeat yourself (single, page, full-width, archive.php. search.php and blog.php)
* Fix error Schema.org markup for wordcount in archive page
* Add lang attribute for HTML tag lang
* Fix navbar display
* Add new class for BreadCrumbs in case the ItalyStrap plugin is not active
* Deprecated old Breadcrumbs function "create_breadcrumbs"
* Improved script for debug
* Add init.php for after_setup_theme and $content_width
* Add content for readme.txt
* Some improvements

= 2.0.0 =
Release Date:

(Dev time 100h)

* Add fully translations in Italian, English, French, German
* Fix php error in search.php (the_ID() outside the loop)
* Add author name in breadcrumbs author page
* Add  get_option('date_format') in meta.php
* Add description in meta.php
* Add carousel-indicators in index.php
* Fix margin in gallery img class
* Modify Favicon function for child theme or partent theme
* Fix issue category icon viewed even if the content is not in category (meta.php)
* Add custom.js file in js/src directory
* Move home.js in js/src
* Add CSS stile for dropdown category in custom.js
* Fix $content_width issue
* Fix echo current page in CPT for Facebook open graph
* Add is_preview() in single.php, page,php and footer.php (for footer only for analytics) (@link http://www.hongkiat.com/blog/wordpress-preview-mode/)
* Update Bootstrap to 3.3.1
* Improve load JS and CSS on hierarchy of page
* Some fix and improvement
* Change license from MIT to GPLv2

= 1.9.2 =

* Add new function for reveal hidden tinymce buttons (styleselect) in new file custom_shortcode.php
* Add button for insert <!--nextpage--> quicktag in the editor
* Retrieve number $posts_per_page from wp backend configuration for blog.php template
* Add rel canonical if SEO Yoast and AIOSP are not installed (cleanup.php)
* Add rel next and prev for paginations (cleanup.php)

= 1.9.1 =

* Fix issue in index.php for no content in CPT Prodotti
* Add rel="noffolow" and button class to comment_reply_link() filter
* Add CSS style img-rounded for all author image

= 1.9.0 =

* Add TGM-Plugin-Activation for require plugin
* Fix object error in breadcrumbs.php
* Add function for adding custom CSS class in get_avatar (Added in comments.php, author.php and author-meta.php)
* Add function for retrieve avatar url
* Improve if statement in author.php


= 1.8.7 =

* Add commented line in custom-post-type.php
* Fix display description for CPT in Archive page archive.php line 34, now display description for all custom post without type slug
* Fix ID's name for author.php (chage in author-page)
* Add <?php create_breadcrumbs() ?> to search.php
* Improve breacrumb.php, now show custom_post_type name
* Improve Read more link in excerpt function (custom_excerpt.php)
* Fix domain name in single.php

= 1.8.6 =

* Change loop in file blog.php, now pagination and excerpt works well
* Add CSS Style for css class in standard WordPress
* Fix category view in meta.php
* Fix display post in index.php when there is a sticky post
* Add img-responsive in wp-caption (cleanup.php)
* Removes img-rounded in add image class image.php

= 1.8.5 =

* Add my name in licence.md
* Add support array with all supports in custom-post-type.php
* Add daschicon in custom post icon
* Add ID to section tag on 404.php, archive.php, author.php, blog.php, ful-width.php, page.php, search.php, single.php, sitemap-html.php
* New file and code for Entry Meta
* Remove img-rounded class and add center-block instead

= 1.8.4 =

* New description README.md
* Fix issue in archive.php
* Add new function for post/page password protection
* Improve italystrap_add_style_and_script function

= 1.8.3 =

* Fix issue "Header already sent"
* Add description echo for custom post type inside a bootstrap's alert

= 1.8.2 =

* Fix some issue in file comments.php (comment-reply.js)

= 1.8.1 =

* Add File readme.txt (Correct theme check issue)
* Renamed file social-button.php in social-button.bak (I will develope soon)
* Add wp standard class in style.css (Correct theme check issue)
* Add wp_link_pages() for pagineted post (Correct theme check issue)
* Replaced bloginfo('url') with echo home_url() (Correct theme check issue)
* Add post_class in search.php file (Correct theme check issue)
* Fix variable issue in widget.php (Correct theme check issue)
* Replaced bloginfo( 'wpurl' ) with echo site_url() in facebook_opengraph (Correct theme check issue)
* Add textdomain in comment-replay.php (Correct theme check issue)
* Modified Root function for new bootstrap class for video
* Replaced get_option('home') with home_url() in breadcrumbs.php (Correct theme check issue)
* Add has_post_format custom function in index.php (Correct theme check issue)
* Add $content_width in functions.php (Correct theme check issue)
* Fix theme check issue in footer.php
* Add pagination to comments.php

= 1.8.0 =

* Update Botstrap to 3.2.0
* Update Gruntfile for build bootstrap js and css after update

= 1.7.3 =

* Add conditional tag for view version only in parent theme

= 1.7.2 =

* Add post_type_archive_title() in archive.php
* Add changelog to file Readme.md

= 1.7.1 =

* Update navwalker to 2.0.4 and add itemprop= to menù
* Built with grunt the javascript task runner

= 1.6.3 =

* Add less file
* Add file with funtction in lib
* Fix some bug

= 1.6.2 =

* Fix some bug

= 1.6.1 =

* Fix some bug

= 1.6.0 =

* Update to Bootstrap 3.1.1

= 1.5.7 =

* Add css class to wrapper all html

= 1.5.6 =

* Fix Warning:Cannot modify header information

= 1.5.5 =

* Migliorata la gestione degli script e degli stili, aggunto CDN fallback

= 1.5.4 =

* Aggiunte funzionalità di roots

= 1.5.3 =

* Migliorata la gestione delle slide in home

= 1.5.1 =

* Corretto problema stile thumb quando non presenti

= 1.5.0 =

* Aggiunto layout per la Sitemap HTML

= 1.4.1 =

* Sostituita classe alle immagini (thumbnail * img-rounded)

= 1.4.0 =

* Aggiornato a Bootstrap 3

= 1.3.3 =

* Separato gli script del file function in un file esterno e commentato riga menu_icon dei custom post type

= 1.3.2 =

* Corretto il tag HTML

= 1.3.1 =

* Aggiunto script per lo slider in home, ora parte in automatico

= 1.3.0 =

* Aggiunto htacces HTML5 Boilerplate

= 1.2.0 =

* Corretti bug e aggiunta classe css img-polaroid come classe default al caricamento di immagini
* Aggiunto codice per i post correlati

= 1.1.1 =

* Migliorata la gestione della description di open graph e twitter card

= 1.1.0 =

* Aggiunto le twitter cards

= 1.0.0 =

* Rilasciata la versione Beta 1.0.0

== Translations ==
 
* English: default, always included.
* Italian: Italiano, sempre incluso.
* German: Deutsch - immer dabei!
* French: Français, toujours inclus.
 
*Note:* This plugins is localized/ translateable by default. This is very important for all users worldwide. So please contribute your language to the plugin to make it even more useful. For translating I recommend the awesome ["Codestyling Localization" plugin](http://wordpress.org/extend/plugins/codestyling-localization/) and for validating the ["Poedit Editor"](http://www.poedit.net/).
 
== Additional Info ==
**Idea Behind / Philosophy:** A theme for improve and add some powerful improvement to your site. I'll try to add more feautures if it makes some sense. So stay tuned :).
 
== Credits ==


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/overclokk/italystrap/trend.png)](https://bitdeli.com/free "Bitdeli Badge")