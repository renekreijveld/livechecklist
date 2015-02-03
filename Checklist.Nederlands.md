Checklist ter controle voor livegang van een nieuwe Joomla! website:

## Jooma!/Extensies
* Niet gebruikte extensies gedepubliceerd of verwijderd?
* Jooma! en alle extensies up-to-date?
* Niet gebruikte templates verwijderd?
* ACL Manager ingericht?

## Jooma! configuratie
* Standaard Captcha ingesteld?
* ReCaptcha private/public keys?
* Foutrapportage uitgeschakeld?
* Algemeen e-mailadres website ingesteld?
* Tijdzone sever goed ingesteld?
* SMTP server ingesteld in de e-mailinstellingen?
* Sessie levensduur ingesteld?
* Template "Preview Module Positions" uitgezet?

## Gebruikers
* Onnodige logins verwijderd?
* Onnodige gebruikersgroepen verwijderd?
* Gebruikersregistratie toestaan uitzetten (indien nodig)
* Wachtwoord complexiteit ingesteld?

## Content
* Oude content opgeschoond?
* Onnodige bestanden/documenten verwijderd, zoals standaard Joomla afbeeldingen?
* Alle Lorem Ipsum / dummy content verwijderd?
* Alle verwijderde content ook echt verwijderd (prullenbak legen artikelen, categorieën, menu items, modules)?
* Development URL's in de database vervangen naar productie URL's?
* Robots.txt goed gezet?
* Favicon aanwezig ([genereer/test](http://realfavicongenerator.net/))?
* Mobiele iconen aanwezig ([genereer/test](http://realfavicongenerator.net/))?
* Redirects oude URL's naar juiste nieuwe URL's ingesteld?
* 404 pagina ingesteld?
* Afbeeldingen geoptimaliseerd?
* Overbodige zoekplugins uit gezet, ook slim zoeken content plugin?
* Zoekplugins in de juiste volgorde?
* Slim zoeken indexen verwijderen en opnieuw opbouwen (als slim zoeken wordt gebruikt)?
* Alle webformulieren hebben e-mail afhandeling en de e-mailadressen goed ingesteld?
* Formulierinzendingen opgeschoond?
* Alle test nieuwsbrieven verwijderd?

## .htaccess
* Redirect non-www to www ingesteld in .htaccess of webserver virtualhostfile?
* Regel toegevoegd zodat XMAP sitemap getoond kan worden als sitemap.xml?

## Beveiliging
* Admin Tools Pro / jHackGuard geïnstalleerd en geconfigureerd?
* Admin Tools Pro Never block these IPs [eigen IP-adres]
* Toegang blokkeren tot /administrator of IP whitelist gebruiken voor /administrator

## JCE Editor
* "optimized" profile ingesteld?
* Jooma! - editors-xtd plugins unpublished?

## XMap
* Sitemap voor menu's aangemaakt?
* XML Sitemap aan Google Webmaster Tools toegevoegd?

## HTTPS
* Certificaat overgezet (indien nodig)?
* HTTPS aangezet (indien nodig)?
* Admin Tools Pro: Convert all links to HTTPS when site is accessed over SSL (indien nodig)

## Optimalisatie / SEO
* SEF URL's / sh404SEF geïnstalleerd en geconfigureerd?
* URL en Meta Tag Manager geïnstalleerd en geconfigureerd?
* MooTools Enabler/Disabler actief? ([Mootools Enabler/Disabler](http://extensions.joomla.org/extension/mootools-enabler-disabler))
* Caching ingesteld?
* Leegmaken cache/tmp mappen?
* JCH Optimize pro / Scriptmerge / jBetolo geïnstalleerd en geconfigureerd?
* CDN geactiveerd?
* Cookie Law / Cookie alert
* Social Share / AddThis geïnstalleerd en geconfigureerd?

## Diversen
* Google Analytics ingesteld?
* Watchful.li ingesteld?
* Backupschema actief?
* Backup EN restore getest?
* FTP login aangemaakt voor beheer?
* Trainingswebsite gearchiveerd en verwijderd?
* Test je website buiten je eigen netwerk/dns
<<<<<<< HEAD
* Test de snelheid van je website. ([YSLOW](http://yslow.org/)), ([PageSpeed Insights](http://developers.google.com/speed/pagespeed/insights/)), ([webpagetest](http://www.webpagetest.org/))
=======
>>>>>>> ef616e2ae194b4417d7a28fa06ba0bb74a391fb5
