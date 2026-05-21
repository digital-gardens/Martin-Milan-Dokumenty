2603-28new-newtab.publ.md

# 2603-27
https://   ___???
musim.obnovit.rukou.traveni.leku/prosim.napiste.10.slov



# 20260521  works extension://icpgjfneehieebagbmdbhnlpiopdcmna/options.html



# https://gemini.google.com/app/a319ecf14c4949be
an existing extension, that could allow me to load a local file


# communtiy at github 
https://github.com/jimschubert/NewTab-Redirect/issues/50

# false alarm?
https://github.com/jimschubert/NewTab-Redirect?tab=readme-ov-file
Important: This is not meant to replace your homepage, only new tabs.
 If your browser is set to load the New Tab page as your homepage, there may be odd consequences.
edge://settings/startHomeNTP
old..probably disabled 

# 20260521  works edge://favorites/?id=45225
edge://settings/startHomeNTP
Open tabs from the previous session
ok
edge:restart 
ok

# 20260521 paranoid research probably not needed but maybe useful in future
Because Edge includes a Startup Boost feature, hidden background processes often remain active even when you close the browser. If your startup flags aren't applying properly, it usually means an old process is still running. You can close all active instances via Task Manager or by running taskkill /f /im msedge.exe before applying your switches.
--disable-gpu: Disables hardware acceleration.--disable-features: Disables specific Chromium or Edge features (e.g., --disable-features=msEdgeStartupBoost).

taskkill /f /im msedge.exe






edge://extensions/?id=icpgjfneehieebagbmdbhnlpiopdcmna
Allow access to file URLs


----
# loop





# zda namirit newtab na 
file:///C:\Users\marti\OneDrive\Dokumenty\011-POMOC.publ.dir/011-POMOC-pro-Martina-Milana.publ.md
nebo na
file:///C:\Users\marti\OneDrive\Dokumenty\eev-f8\TODO.f8.md
edge://favorites/?id=45225
# 20260521  works extension://icpgjfneehieebagbmdbhnlpiopdcmna/options.html
© James Schubert, 2009-2023  |  Report bugs  |  Beta test  |  'Welcome'



https://github.com/jimschubert/NewTab-Redirect?tab=readme-ov-file

https://github.com/jimschubert/newtab-redirect/wiki
uz jsem procetl faq







OLD2603-28newtab.publ.md
dont needmkdir 2603-28newtab 


# next time 
maybe 
i start with 
start with 
extension://icpgjfneehieebagbmdbhnlpiopdcmna/options.html

there are 4 grant options 

permissions are optional


  
  
  
  extension://icpgjfneehieebagbmdbhnlpiopdcmna/options.html
  [New Tab Redirect Options](chrome-extension://icpgjfneehieebagbmdbhnlpiopdcmna/options.html) [Chrome Web Store](https://chrome.google.com/webstore)

- URL
- Permissions
- Contact
- Donate

 

## Redirect URL


file:///C:\Users\marti\OneDrive\Dokumenty\eev-f8\TODO.f8.md

 Save Cancel 

 Always update tab, not redirect. (Enable for cursor in the address bar)
?
not needed yet 


 Sync this URL across browsers?

### One click save...

#### Popular Pages

 [Facebook](https://www.facebook.com/)

 [Twitter](https://twitter.com/)

 [Reddit](https://www.reddit.com/)

 [Wikipedia](https://www.wikipedia.org/)

 [Yahoo](https://www.yahoo.com/)

 [Digg](https://digg.com/)

 [Slashdot](https://www.slashdot.org/)

#### Chrome Pages

 [Chrome Apps](chrome://apps/)

 [Extensions](chrome://extensions/)


aaa [History](chrome://history/)


 [Downloads](chrome://downloads/)

aa [Bookmarks](chrome://bookmarks/)

 [Internals](chrome://net-internals/)

 [Devices](chrome://devices/)

 [Flags](chrome://flags/)

 [Inspect](chrome://inspect/)

 [Memory](chrome://memory-redirect/)

 [Version](chrome://version/)

 [Blank Page](about:blank)



Options saved!

[© James Schubert, 2009-2023](http://www.ipreferjim.com/)  |  [Report bugs](http://github.com/jimschubert/newtab-redirect)  |  [Beta test](https://groups.google.com/forum/#!forum/new-tab-redirect-beta-testers)  |  ['Welcome'](chrome-extension://icpgjfneehieebagbmdbhnlpiopdcmna/welcome.html)


---
## Permissions

For information regarding what these permissions mean, please research:

- [Chrome extensions: permission warnings](http://developer.chrome.com/extensions/permission_warnings)
- [Chrome Web Store Help: Permissions requested by apps and extensions](https://support.google.com/chrome_webstore/answer/186213?hl=en)

If you have any doubts or questions, email me at james.schubert@gmail.com.

Never enable permissions you don't trust or don't understand, it can be dangerous.

### Required Permissions

- storage
- favicon

### Optional Permissions

- tabs Approve Deny
- topSites Approve Deny
- management Approve Deny
- bookmarks Approve Deny

### Where these are used

The _required permissions_ are used mostly by the options page.

They allow the extension to display icons and save data either locally or to your Google Account (if you've enabled syncing in your browser and enabled extension syncing).

The _optional permissions_ are used by the custom new tab 'Apps' page.

All of the optional permissions provide more functionality than the 'Apps' page needs, but extensions have to select permissions in their entirety for even a small subset of abilities. Here's how the 'Apps' page uses them.

_tabs_: **"Access your tabs and browsing activity"**

The 'tabs' permission is used to open apps in a new window (available in the rollover links). It's a nice-to-have feature, but is not necessary. If you don't trust this permission, leave it disabled. Only power users would be opening apps in new windows. See the [development documents](http://developer.chrome.com/extensions/tabs "tabs summary") for more.

_topSites_: **"Read and modify your browsing history"**

This permission is bundled in the same warning as the history permission (which isn't used by this extension). The 'topSites' permission simply allows getting the top 20 most visited sites. The warning you get when enabling this permission is silly because it can't read any more of your history than the recent sites, and has no way to modify your history. See the [development documents](http://developer.chrome.com/extensions/topSites "topSites summary") for more.

_management_: **"Manage your apps, extensions, and themes"**

The custom 'Apps' page only needs the 'apps' part of this permission. In fact, I have to filter out extensions and themes because everything is returned in the query. By 'manage', this means the extension can allow you to view, create, edit, or delete apps. Currently, the custom 'Apps' page retrieves apps and allows you to uninstall apps directly from within the 'Apps' page. You're provided confirmation. Generally, you should be cautious about enabling this permission in extensions, because it also allows extensions to install apps or uninstall the extension itself. Unfortunately, the permission is all or nothing, otherwise I'd request the bare minimum. This is the only required permission for the custom 'Apps' page to make sense. See the [development documents](http://developer.chrome.com/extensions/management "management summary") for more.

_bookmarks_: **"Read and modify your bookmarks"**

Again, an all-or-nothing permission. The 'Apps' page can display between 5 and 40 bookmarks from your bookmarks bar. There's no modification going on. See the [development documents](http://developer.chrome.com/extensions/bookmarks "bookmarks summary") for more.
---


---
---
---
---
---
---
---
  











# next time i will 
probably ignore 
ignore the newtab
gear 
3 options 


# copied here using inspect and obsidian copy paste

---

----- sdfsfdfsd


---

## Display Preferences

### Bookmarks Bar

Grant 'bookmarks' Permission

 Enable

Show  bookmarks
10

### Top Sites Panel

Grant 'topSites' Permission

 Enable

Show  top sites
10

### Open apps in New Window

Grant 'tabs' Permission

Close

---

---

---

---


		<hr/>
		<hr/>
		<hr/>
		<hr/>

  [New Tab Redirect!](options.html) [Chrome Web Store](https://chrome.google.com/webstore)

No matches found.

### Hello.

This extension doesn't yet have the permissions to read and manage your Apps! It requires the 'management' permission to do this. You can read more about [permissions](https://support.google.com/chrome_webstore/answer/186213?hl=en) and their [warnings](http://developer.chrome.com/extensions/permission_warnings) before proceeding.

Grant 'management' Permission

Permissions and display options can be configured by clicking the gear icon in the bottom right corner. That's where you'll find extra, opt-in functionality like the top sites panel and quick bookmarks 'bar'.

You'll only see that annoying popup to request permissions once. After that, you can grant or deny any individual permissions at any time without the extra popup (except the management permission, because what good's an Apps page without that?).

Enable what you want, disable what you don't. You can always check the permissions of any installed extension or app at chrome://extensions (also accessible under `Menu -> Tools -> Extensions`. Safe browsing!


### Hello.

  [New Tab Redirect!](chrome-extension://icpgjfneehieebagbmdbhnlpiopdcmna/options.html) 
  [Chrome Web Store](https://chrome.google.com/webstore)


This extension doesn't yet have the permissions to read and manage your Apps! It requires the 'management' permission to do this. You can read more about [permissions](https://support.google.com/chrome_webstore/answer/186213?hl=en) and their [warnings](http://developer.chrome.com/extensions/permission_warnings) before proceeding.

Grant 'management' Permission

Permissions and display options can be configured by clicking the gear icon in the bottom right corner. That's where you'll find extra, opt-in functionality like the top sites panel and quick bookmarks 'bar'.

You'll only see that annoying popup to request permissions once. After that, you can grant or deny any individual permissions at any time without the extra popup (except the management permission, because what good's an Apps page without that?).

Enable what you want, disable what you don't. You can always check the permissions of any installed extension or app at chrome://extensions (also accessible under `Menu -> Tools -> Extensions`. Safe browsing!




  New Tab Redirect! Chrome Web Store
### Hello.
This extension doesn't yet have the permissions to read and manage your Apps! It requires the 'management' permission to do this. You can read more about permissions and their warnings before proceeding.

Grant 'management' Permission

Permissions and display options can be configured by clicking the gear icon in the bottom right corner. That's where you'll find extra, opt-in functionality like the top sites panel and quick bookmarks 'bar'.

You'll only see that annoying popup to request permissions once. After that, you can grant or deny any individual permissions at any time without the extra popup (except the management permission, because what good's an Apps page without that?).

Enable what you want, disable what you don't. You can always check the permissions of any installed extension or app at chrome://extensions (also accessible under Menu -> Tools -> Extensions. Safe browsing!












