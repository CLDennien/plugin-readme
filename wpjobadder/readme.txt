=== WP Job Adder ===
Contributors: cdennien
Tags: wpjobadder, jobadder, job
Requires at least: 5.4
Tested up to: 6.2
Stable tag: 1.0.2
Requires PHP: 7.4
License: GNU General Public License v2.0
License URI: https://www.gnu.org/licenses/gpl-2.0.html

WP Job Adder is a lightweight job fetching plugin for JobAdder. This plugin is a integration for WP Job Manager.

== Description ==

WP Job Adder is a lightweight job fetching plugin for JobAdder. This plugin is a integration for WP Job Manager, therefor the WP Job Manager plugin must be installed and activated.

#### Features:

*   Fetch multiple JobAdder xml files, just separate the urls by a `|` character.
*   Jobs are fetched in the background hourly.
*   Integration with ACF.

#### Documentation

To be added in the future...

#### Support

Use the WordPress.org forums for community support where we try to help all users. Otherwise send us a [support ticket](https://wpjobadder.kinsta.cloud)

== Frequently Asked Questions ==

= How to I customise the import? =

All WP Job Adder settings are found in the admin menu `Settings -> WP Job Adder`.

== Installation ==
1. Upload 'wp-job-adder.zip' to the `Plugins -> Add New -> Upload Plugin` section of your dashboard.
2. Activate the plugin in the `Plugins` section.

== Changelog ==

#### 1.0.2

*   Fix: Overide $api->version with $api->stable_version.

#### 1.0.1

*   Fix: Cron fires reliably now.
*   Enhancement: Add `Run Now` link to `Plugins` section.
*   Enhancement: Log job import errors.
*   Enhancement: Handle multiple xml files, separate by `|` character.

#### 1.0.0

*   Init: First complete version of the plugin.
