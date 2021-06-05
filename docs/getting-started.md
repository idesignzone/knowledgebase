---
title: Getting started
date: 2018-09-15T07:42:34.000+00:00
slug: getting-started

---
## What is Gridbox

Gridbox is a headless Wordpress website builder that makes use of [Wordpress](https://wordpress.org/ "WordPress") backend and default [Gutenberg](https://wordpress.org/gutenberg/ "Gutenberg") editor to create and manage your website content and display in a [Gridsome](https://gridsome.org/ "Gridsome") website. 

## Prerequisite

Traditional [WordPress](https://wordpress.org/ "WordPress") consist of the admin panel and the front-end that are tied together. A headless WordPress in the other hand do separate these. Make sure your development environment is ready for both back-end and front-end. 

**Recommended setup to run WordPress**

* [PHP](https://www.php.net/) version 7.4 or greater.
* [MySQL](https://www.mysql.com/) version 5.6 or greater _OR_ [MariaDB](https://mariadb.org/) version 10.1 or greater.
* [HTTPS](https://wordpress.org/news/2016/12/moving-toward-ssl/) support

**Recommended setup to run Gridsome**

* [Node.js](https://nodejs.org/ "Node.js") (v8.3+) 
*  [Yarn](https://yarnpkg.com/)

## Local installation

There are 2 major stages for setting up your project locally

1. Installing WordPress and configuring the back-end
2. Running the Gridsome front-end

```bash
git clone https://github.com/samuelhorn/jamdocs project-name
cd project-name
gridsome develop
```