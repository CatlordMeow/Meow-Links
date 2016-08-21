# Meow-Links
Required version of vBulletin: 4, although I want to believe that it will work on vB 3, too.

This product changes the way forum handles links in new messages those aren't inside of any BB codes.
By default, vBulletin just wraps them inside url code.

## What Meow! Links Does
- URL title is getting replaced with a title of referenced page;
so, after installing this product, all newly posted links will be looking like this:

[PHP: Hypertext Preprocessor](http://php.net)
[Stack Overflow](http://stackoverflow.com/)
[/b/ - Random - 4chan](http://boards.4chan.org/b/)
- Links to pictures will be wrapped inside img code; so, instead of link, an image itself will be shown.
Detecting 'is it picture or not' is made by extension (.gif, .jpg, .png...).
- Links to videos on YouTube will be wrapped inside video code.

The product can be configured.

Default language is English, Russian translation is provided.

## Installation
Admin Control Panel => Plugins & Products => Manage Products => Add/Import Product => Browse => pick Meow!-Links-1.x.xml => Import.

## Credits
Meow! Links is rewritten and revamped Title Tag Fetcher by exportforce, which, in turn, is based on Replace URL's With Page Title from Jafo232.

Patch for encoding detection is made by kerk.

## Differences from Mentioned Add-ons
### Added
- Wrapping links to pictures inside img code.
- Wrapping links to YouTube's videos inside video code.
- Settings.

### Fixed
- Compatibility with site [http://knowyourmeme.com/](http://knowyourmeme.com/), and also all others those don't give a content without user-agent specified.
- Encoding detection. Will work with non-English pages (I hope).

## Additional Information
IMPORTANT: for creating 'beautified' links forum will download a page for every link.

In fact, users of your forum will be giving orders to your server for connection and downloading by random addresses on Internet.

If some user posts 10 links, there will be 10 connections and downloads.

If 100 (hundred) links -- 100 connections will happen.

## See also
### vbulletin.org
- [Replace URL's With Page Title](http://www.vbulletin.org/forum/showthread.php?t=155909)
- [Title Tag Fetcher (Auto Replace URL with Titletag)](http://www.vbulletin.org/forum/showthread.php?t=189658)
- [Auto Youtube Link-Converter](http://www.vbulletin.org/forum/showthread.php?t=261296)
- [Automatic Youtube And Images Replacer](http://www.vbulletin.org/forum/showthread.php?t=261595)
- [Auto youtube player](http://www.vbulletin.org/forum/showthread.php?t=283432)