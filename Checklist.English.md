Checklist for when a Joomla! website goes live:

## Joomla!/Extensions
* Unpublish or uninstalled all unused extensions?
* Joomla and all extensions are up-to-date?
* Uninstalled all unused templates?
* ACL Manager installed and configured?

## Joomla! configuration
* ReCaptcha private/public keys?
* Default Captcha set?
* Error reporting disabled?
* General email address setup?
* Mail Settings setup and SMTP server setup?
* Mass Mail disabled?
* Server timezone set correctly?
* Session settings setup?
* Template "Preview Module Positions" disabled?
* Feed Email Address to "No Email"?

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

## Layout
* Website tested in all major browsers (OSX: Safari, Chrome, Firefox. Windows: IE, Edge, Chrome, Firefox.)
* Mobile template present and tested?

## .htaccess
* Redirect non-www to www setup in .htaccess?
* Redirect non-ssl to ssl setup in .htaccess?

## Security
* Admin Tools Pro / jHackGuard / AdminExile installed and configured?
* Prevent blocking own IP-addresses
* Block access to /administrator with admin secret URL parameter or use IP whitelist for /administrator

## JCE Editor
* optimized profile added/configured?
* Joomla! - editors-xtd plugins unpublished?

## OSMap
* Sitemap created for all menus?
* Add line to .htaccess to show OSXMAP sitemap as sitemap.xml? ([example] (https://gist.github.com/hans2103/aec679d235ff76e33822)) Carefull: use a different solution for multilingual sites.
* XML Sitemap added to Google Webmaster Tools?

## HTTPS
* Certificate setup (if necessary)?
* Activated HTTPS (if necessary)?

## Optimisation / SEO
* Search-engine friendly URLs installed and configured?
* Mootools enabler/disabler active? ([Mootools Enabler/Disabler](http://extensions.joomla.org/extension/mootools-enabler-disabler))
* Caching setup?
* Cleared cache/tmp folders?
* Varnish setup?
* CSS/Javascript compress/merge installed and configured?
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
* Speed checked of the website? ([YSLOW](http://yslow.org/)), ([PageSpeed Insights](http://developers.google.com/speed/pagespeed/insights/)), ([webpagetest](http://www.webpagetest.org/)), ([yellowlabs](http://yellowlab.tools/))
