Checklist for when a Joomla! website goes live:

## Joomla!/Extensions
* Unpublish or uninstalled all unused extensions?
* Joomla and all extensions are up-to-date?
* Uninstalled all unused templates?
* ACL Manager installed and configured?

## Joomla! configuration
* Default Captcha set?
* ReCaptcha private/public keys?
* Error reporting disabled?
* General email address setup?
* Server timezone set correctly?
* Mail Settings setup and SMTP server setup?
* Session settings setup?
* Template "Preview Module Positions" disabled?

## Users
* Removed all unused logins?
* Allow User Registration: no (if necessary)?
* Password complexity setup?

## Content
* Removed all unused content?
* Removed all unused files and images?
* Removed all deleted content (empty trash articles, categories, menu items, modules)?
* Replaced development URLs in the database with production URLs?
* Robots.txt setup?
* Favicon installed?
* URL redirects from old site to new site setup?
* Added a 404 page?
* Optimized images?
* Unpublished unused search plugins?
* Are the search plugins in the correct order?

## .htaccess
* Redirect non-www to www setup in .htaccess?
* Added line to show XMAP sitemap as sitemap.xml?

## Security
* Admin Tools Pro / jHackGuard installed and configured?
* Admin Tools Pro Never block these IPs [your own IP-address]
* Block access to /administrator with admin secret URL parameter or use IP whitelist for /administrator

## JCE Editor
* optimized profile added/configured?
* Joomla! - editors-xtd plugins unpublished?

## XMap
* Sitemap created for all menus?
* XML Sitemap added to Google Webmaster Tools?

## HTTPS
* Certificate setup (if necessary)?
* Activated HTTPS (if necessary)?
* Admin Tools Pro: Convert all links to HTTPS when site is accessed over SSL (if necessary)

## Optimisation / SEO
* SEF URLs / sh404SEF installed and configured?
* URL and Meta Tag Manager installed and configured?
* Mootools enabler/disabler active?
* Caching setup?
* Cleared cache/tmp folders?
* JCH Optimize pro / Scriptmerge / jBetolo installed and configured
* CDN activated?
* Cookie Law / Cookie alert
* Social Share / AddThis installed and configured?

## Diversen
* Google Analytics setup?
* Watchful.li setup?
* Is there a backup scheme?
* Backup AND restore tested?
* FTP login created for support?
