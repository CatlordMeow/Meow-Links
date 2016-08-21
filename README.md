# Meow-Links
Required version of vBulletin: 4, although I want to believe that it will work on vB 3, too.

This product changes the way forum handles links in new messages those aren't inside of any BB codes.
By default, vBulletin just wraps them inside url code.

##What Meow! Links Does
URL title is getting replaced with a title of referenced page;
so, after installing this product, all newly posted links will be looking like this:
[url=http://php.net/]PHP: Hypertext Preprocessor[/url]
[url=http://stackoverflow.com/]Stack Overflow[/url]
[url=http://boards.4chan.org/b/]/b/ - Random - 4chan[/url]
[*]Links to pictures will be wrapped inside img code; so, instead of link, an image itself will be shown.
Detecting 'is it picture or not' is made by extension (.gif, .jpg, .png...).
[*]Links to videos on YouTube will be wrapped inside video code.
[/LIST]

The product can be configured.
Default language is English, Russian translation is provided.

[SIZE=3]Installation[/SIZE]
[COLOR="#FFFFFF"][HR][/HR][/COLOR]
Admin Control Panel => Plugins & Products => Manage Products => Add/Import Product => Browse => pick Meow!-Links-1.x.xml => Import.

[SIZE=3]Credits[/SIZE]
[COLOR="#FFFFFF"][HR][/HR][/COLOR]
Meow! Links is rewritten and revamped Title Tag Fetcher by exportforce, which, in turn, is based on Replace URL's With Page Title from Jafo232.

Patch for encoding detection is made by kerk.

[SIZE=3]Differences from Mentioned Add-ons[/SIZE]
[COLOR="#FFFFFF"][HR][/HR][/COLOR]
[SIZE=2]Added[/SIZE]

[LIST]
[*]Wrapping links to pictures inside img code.
[*]Wrapping links to YouTube's videos inside video code.
[*]Settings.
[/LIST]

[SIZE=2]Fixed[/SIZE]

[LIST]
[*]Compatibility with site [url=http://knowyourmeme.com/]http://knowyourmeme.com/[/url], and also all others those don't give a content without user-agent specified.
[*]Encoding detection. Will work with non-English pages (I hope).
[/LIST]

[SIZE=3]Additional Information[/SIZE]
[COLOR="#FFFFFF"][HR][/HR][/COLOR]
IMPORTANT: for creating 'beautified' links forum will download a page for every link.
In fact, users of your forum will be giving orders to your server for connection and downloading by random addresses on Internet. 
If some user posts 10 links, there will be 10 connections and downloads.
If 100 (hundred) links -- 100 connections will happen.

[SIZE=3]See also[/SIZE]
[COLOR="#FFFFFF"][HR][/HR][/COLOR]
[SIZE=2]github[/SIZE]

[LIST]
[*][url=https://github.com/CatlordMeow/Misc/blob/master/Meow!-Links.xml]Meow!-Links.xml[/url]
[*][url=https://github.com/CatlordMeow/Misc/blob/master/Meow!-Links-rus-cp1251.xml]Meow!-Links-rus-cp1251.xml[/url]
[*][url=https://github.com/CatlordMeow/Misc/blob/master/Meow!-Links-rus-utf-8.xml]Meow!-Links-rus-utf-8.xml[/url]
[/LIST]

[SIZE=2]vbulletin.org[/SIZE]

[LIST]
[*][url=http://www.vbulletin.org/forum/showthread.php?t=155909]Replace URL's With Page Title[/url]
[*][url=http://www.vbulletin.org/forum/showthread.php?t=189658]Title Tag Fetcher (Auto Replace URL with Titletag)[/url]
[*][url=http://www.vbulletin.org/forum/showthread.php?t=261296]Auto Youtube Link-Converter[/url]
[*][url=http://www.vbulletin.org/forum/showthread.php?t=261595]Automatic Youtube And Images Replacer[/url]
[*][url=http://www.vbulletin.org/forum/showthread.php?t=283432]Auto youtube player[/url]
[/LIST]
