---
title: Getting started
date: 2021-12-26
slug: getting-started

---
## What is Gridbox

Gridbox is a headless Wordpress website builder that makes use of [Wordpress](https://wordpress.org/ "WordPress") and its default [Gutenberg](https://wordpress.org/gutenberg/ "Gutenberg") editor to create and manage your website content and display in a [Gridsome](https://gridsome.org/ "Gridsome") website.

## Prerequisite

Traditional [WordPress](https://wordpress.org/ "WordPress") consist of the admin panel and the website that are tied together. A headless WordPress in the other hand do separate these. Make sure your development environment is ready for both back-end and front-end.

**Recommended setup to run WordPress**

* [PHP](https://www.php.net/) version 7.4 or greater.
* [MySQL](https://www.mysql.com/) version 5.6 or greater _OR_ [MariaDB](https://mariadb.org/) version 10.1 or greater.
* [HTTPS](https://wordpress.org/news/2016/12/moving-toward-ssl/) support

**Recommended setup to run Gridsome**

* [Node.js](https://nodejs.org/ "Node.js") (v8.3+)
* [Yarn](https://yarnpkg.com/)

## Installation

There are 2 steps for setting up your project

1. [Installing WordPress](https://wordpress.org/support/article/how-to-install-wordpress/) and configuring Gridbox Theme
2. [Running Gridsome](https://gridsome.org/docs/gridsome-cli/) front-end

## Domain Structure

[Install WordPress](https://wordpress.org/support/article/how-to-install-wordpress/) on a subdomain and NOT the main domain. For example if your website domain is mywebsite.com, your WordPress installation should be on wordpress.mywebsite.com. This way we reserve the main domain for the front-end that will be deployed on a serverless platform.

## Installing the theme

After you have installed WordPress, you can start installing Gridsome theme following these steps:

1. In your WordPress admin go to Appearance/Themes - Add New and upload both gridbox-theme and gridbox-child-theme.
2. Activate Gridbox Child theme
3. Go to Appearance/Install Plugins and start Installing required plugins. Make sure plugins are activated.

## Import Demo Data

You can import the demo content shown in the demo to your WordPress installation. To import one of the predefined demos go to Appearance/Import Demo Data and select your ideal demo and click import.

After you have imported the demo content, you can delete "**One Click Demo Import"** plugin as we don't need it anymore.