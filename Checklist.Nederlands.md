Checklist ter controle voor livegang van een nieuwe Joomla! website:

## Joomla!/Extensies
* Niet gebruikte extensies gedepubliceerd of verwijderd?
* Joomla! en alle extensies up-to-date?
* Niet gebruikte templates verwijderd?
* ACL Manager ingericht?

## Joomla! configuratie
* ReCaptcha private/public keys?
* Standaard Captcha ingesteld?
* Foutrapportage uitgeschakeld?
* Algemeen e-mailadres website ingesteld?
* Feed Email Address op "No Email"?
* SMTP server ingesteld in de e-mailinstellingen?
* Groepsmail uitgeschakeld?
* Tijdzone server goed ingesteld?
* Sessie levensduur ingesteld?
* Template "Preview Module Positions" uitgezet?

## Gebruikers
* Onnodige Gebruikers uit Gebruikersbeheer verwijderd?
* Onnodige Gebruikersgroepen verwijderd?
* Gebruikersregistratie toestaan uitgezet? (indien nodig)
* Wachtwoord complexiteit ingesteld?

## Content
* Oude content opgeschoond?
* Onnodige bestanden/documenten verwijderd, zoals standaard Joomla afbeeldingen?
* Alle Lorem Ipsum / dummy content verwijderd?
* Alle verwijderde content verwijderd (prullenbak leeg artikelen, categorieën, menu items, modules)?
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

## Layout
* Website getest in alle hoofdbrowsers (OSX: Safari, Chrome, Firefox. Windows: IE, Edge, Chrome, Firefox.)
* Mobiele template aanwezig en getest?

## .htaccess
* Redirect non-www naar www ingesteld in .htaccess?
* Redirect non-ssl naar ssl ingesteld in .htaccess?

## Beveiliging
* Admin Tools Pro / jHackGuard / AdminExile geïnstalleerd en geconfigureerd?
* Voorkom blokkade eigen IP-adressen
* Toegang blokkeren tot /administrator of IP whitelist gebruiken voor /administrator

## JCE Editor
* "optimized" profiel ingesteld?
* Joomla! - editors-xtd plugins unpublished?

## OSMap
* Sitemap voor menu's aangemaakt?
* Regel toegevoegen aan .htaccess zodat OSMAP sitemap getoond kan worden als sitemap.xml? ([voorbeeld] (https://gist.github.com/hans2103/aec679d235ff76e33822)) Let op: gebruik een andere oplossing voor meertalige websites.
* XML Sitemap aan Google Webmaster Tools toegevoegd?

## HTTPS
* Certificaat overgezet (indien nodig)?
* HTTPS aangezet (indien nodig)?

## Optimalisatie / SEO
* Zoekmachine-vriendelijke URL's geïnstalleerd en geconfigureerd?
* MooTools Enabler/Disabler actief? ([Mootools Enabler/Disabler](http://extensions.joomla.org/extension/mootools-enabler-disabler))
* Caching ingesteld?
* Leegmaken cache/tmp mappen?
* Varnish ingesteld?
* CSS/Javascript compress/merge geïnstalleerd en geconfigureerd?
* CDN geactiveerd?
* Cookie Law / Cookie alert
* Social Share / AddThis geïnstalleerd en geconfigureerd?

## Diversen
* Google Analytics ingesteld?
* Watchful.li ingesteld? ([Watchful.li](https://watchful.li/))
* myJoomla audit gedaan? ([{manage}.myJoomla.com](https://myjoomla.com/))
* Joomla Updatemelding plugin gepubliceerd/gedepubliceerd?
* Backupschema actief?
* Backup EN restore getest?
* Loglevel in Akeeba Backup profiel ingesteld of op geen loggin gezet?
* (S)FTP login aangemaakt voor beheer?
* Trainingswebsite gearchiveerd en verwijderd?
* Website getest buiten je eigen netwerk/dns?
* Snelheid getest van de website? ([GTMetrix](https://gtmetrix.com/)), ([PageSpeed Insights](http://developers.google.com/speed/pagespeed/insights/)), ([webpagetest](http://www.webpagetest.org/)), ([yellowlabs](http://yellowlab.tools/))
