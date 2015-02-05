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
* Removed all unused Users from User Manager?
* Removed all unused User Groups?
* Allow User Registration: no (if necessary)?
* Password complexity setup?

## Content
* Removed all unused content?
* Removed all unused files and images, like default Joomla images?
* All Lorem Ipsum / dummy content is removed?
* Removed all deleted content (empty trash articles, categories, menu items, modules)?
* Replaced development URLs in the database with production URLs?
* Robots.txt setup?
* Favicon installed ([generate/test](http://realfavicongenerator.net/))?
* Mobile icons installed ([generate/test](http://realfavicongenerator.net/))?
* URL redirects from old site to new site setup?
* Added a 404 page?
* Optimized images?
* Unpublished unused search plugins, also the smart search plugin?
* Are the search plugins in the correct order?
* Clear smart search indexes and rebuild them (if smart search is used)?
* All webforms have email handling and emailadresses setup correctly?
* Cleaned form submissions?
* Cleaned all test newsletters?

## .htaccess
* Redirect non-www to www setup in .htaccess or webserver hostfile?
* Added line to show XMAP sitemap as sitemap.xml? ([example] (https://gist.github.com/hans2103/aec679d235ff76e33822))

## Security
* Admin Tools Pro / jHackGuard installed and configured?
* Admin Tools Pro Never block these IPs [your own IP-address]
* Block access to /administrator with admin secret URL parameter or use IP whitelist for /administrator

## JCE Editor
* optimized profile added/configured?
* Joomla! - editors-xtd plugins unpublished?

## XMap
* Sitemap created for all menus?
* XML Sitemap added to Google Webmaster Tools? ([example](https://gist.github.com/hans2103/aec679d235ff76e33822))

## HTTPS
* Certificate setup (if necessary)?
* Activated HTTPS (if necessary)?
* Admin Tools Pro: Convert all links to HTTPS when site is accessed over SSL (if necessary)

## Optimisation / SEO
* SEF URLs / sh404SEF installed and configured?
* URL and Meta Tag Manager installed and configured?
* Mootools enabler/disabler active? ([Mootools Enabler/Disabler](http://extensions.joomla.org/extension/mootools-enabler-disabler))
* Caching setup?
* Cleared cache/tmp folders?
* JCH Optimize pro / Scriptmerge / jBetolo installed and configured
* CDN activated?
* Cookie Law / Cookie alert
* Social Share / AddThis installed and configured?

## Extras
* Google Analytics setup?
* Watchful.li setup? ([Watchful.li](https://watchful.li/))
* myJoomla audit done? ([{manage}.myJoomla.com](https://myjoomla.com/))
* Is there a backup scheme?
* Backup AND restore tested?
* (S)FTP login created for support?
* Trainingwebsite archived and removed?
* Website checked outside your own network/dns?
* Speed checked of the website? ([YSLOW](http://yslow.org/)), ([PageSpeed Insights](http://developers.google.com/speed/pagespeed/insights/)), ([webpagetest](http://www.webpagetest.org/)) 
