=== Collapsing Categories List ===
Contributors: migrad
Tags: collaps, collapsing, category, list, categories, subcategory, subcategories, parent, child, hide, remove, link, order, expand, limit, admin, block, edit, post
Requires at least: 3.4.2
Tested up to: 5.0
Stable tag: 0.5.5
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

This plugin modifies the categories block to add new features such as collapse and expand categories and subcategories, order, etc. 
It also allows you to limit the number of categories and subcategories that can be selected in the edit post page.

== Description ==

= Frontend =
This plugin allows you to display and collapse the tree of subcategories of categories that have at least one subcategory.

Features:

* Collaps and expand subcategories.
* Remove links of all or some categories.
* Hide one or several categories.
* Change the images with plus and minus symbols for other images that represent collapsed or expanded categories, or css icons.
* Order categories list by name and slug.
* Hide icons for expand/collapse if you don't want it.
* Collapse all categories when show a post page or maintain expand the category related with the post.
* Maintain expand all or some categories.

= If your WordPress theme don't use the widget categories list of WordPress, this plugin maybe don't work. =

= Backend =
This plugin allows you can to limit the number of categories and subcategories selectables in the categories list block in edit post page.

Features:

* Limit the number of categories or subcategories selectables in the categories list block in edit post page.
* Admin page for custom this limit for category level.

== Installation ==

= If your WordPress theme don't use the widget category list of WordPress, this plugin maybe don't work. =

= Frontend =
* Go to Appearance/Widgets menu.
* Show widget categories settings.
* Activate the option "Show hierarchy"
* Activate the option "Collaps categories" and Save.
* Customize to your taste.

= Backend =
* Go to Settings/Collapsing category list menu.
* Active the checkbox "Limit the selection of categories and subcategories...".
* Indicates the maximum number of selectable categories and / or subcategories or leave it as zero so there is no limit.
* Add other limits for others levels of subcategories.

== Frequently Asked Questions ==

Nothing for now

== Screenshots ==

1. Detailed list of categories with subcategories collapsed.
2. Detailed list of categories with subcategories deployed.
3. Detail widget settings categories.
4. Detail of the plugin admin page.
5. Detail of th categories list block of edit post page.

== Changelog ==
= 0.5.5 =
* Now collapse the categories on all pages except category pages and posts. Thanks to @paperkawaii

= 0.5.4 = 
* Fixed error array_key_exists() in backend

= 0.5.3 =
* Updated to WordPress 4.9

= 0.5.2 =
* Update APF library to version 3.8.15
* Minor bugs

= 0.5.1 =
* Fixed an error with a class.

= 0.5 =
* New feature: Admin page for custom the categorories list block in edit post page.
* New feature: Limit the categories and subcategories selectables of the categories list block
in edit post page.
* Translations for English and Spanish.
* Readme.txt updated.
* Screenshots updated.
* Updated to WordPress 4.7

= 0.4.2 =
* Bug fixed: Only expand the first parent of the current category.

= 0.4.1 =
* Updated to WordPress 4.6

= 0.4 =
* New feature: To collapse all categories on the page post.
* Bug fixed: To expand the category related with the post.
* Bug fixed: Remove url from categories add in the "Remove link of categories by title" field.
* Add I18n files.
* Translations for English and Spanish.
* Updated readme.txt

= 0.3.1 =
* Updated to WordPress 4.5

= 0.3 =
* Updated to WordPress 4.4
* New icons for collapse / expand categories for responsive design with font-awesome
* Add checkbox for activate news icons or old images.
* Add checkbox for hide plus and minus icons.

= 0.2.3 =
* Fixed little bugs

= 0.2.1 =
* Categories list can be ordered by name or slug
* One or several categories can be always expanded
* Change text "Remove parent link" for "Remove all links"
* Fixed a bug with dropdown order

= 0.2 =
* Categories list can be ordered by name or slug
* One or several categories can be always expanded
* Change text "Remove parent link" for "Remove all links"

= 0.1.1 =
* Updated to WordPress 4.1

= 0.1.0 =
* Updated to WordPress 4.0
* Fixed a problem with categories' children

= 0.0.9 =
* Updated to WordPress 3.9
* Fixed a problem with images in Twenty Fourteen theme and Twenty Thirteen theme

= 0.0.8 =
* Updated to WordPress 3.8
* Add two new images for Twenty Fourteen theme and Twenty Thirteen theme
* Now the plugin remove the link in categories correctly

= 0.0.7 =
* Change the id for class on 'a' tag
* Add the possibility change images of collase and expand
* Add the option of remove parent link
* Add the option for hide categories
* Add the option for remove the link in some categories

= 0.0.6.1 =
* Minor changes

= 0.0.6 =
* Fixed a problem with expanded categories
* Update to WordPress 3.6

= 0.0.5.1 =
* Minor changes

= 0.0.5 =
* New option in the categories widget's configuration for activate or deactivate the filter.

= 0.0.4 =
* The plugin remain selected subcategories

= 0.0.3 =
* Updated to WordPress 3.5

= 0.0.2 =
* Minor changes

= 0.0.1 =
* First version

== Upgrade Notice ==

= 0.5 =
* New feature: Admin page for custom the categorories list block in edit post page.
* New feature: Limit the categories and subcategories selectables of the categories list block
in edit post page.
* Translations for English and Spanish.
* Readme.txt updated.
* Screenshots updated.
* Updated to WordPress 4.7
