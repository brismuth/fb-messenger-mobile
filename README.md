# fb-messenger-mobile
A set of CSS rules to make Facebook messenger usable on mobile browsers. This is a work in progress.

## How to use it
Add a bookmarklet with this URL:

```javascript:(function(){var s=document.createElement('link');s.setAttribute('href','https://cdn.jsdelivr.net/gh/brismuth/fb-messenger-mobile@master/override.css');s.setAttribute('rel','stylesheet');s.setAttribute('type','text/css');document.getElementsByTagName('head')[0].appendChild(s);var meta = document.createElement('meta'); meta.name = "viewport"; meta.content = "width=device-width, initial-scale=0.65, maximum-scale=0.65"; document.getElementsByTagName('head')[0].appendChild(meta);})();```

Here is a guide on adding bookmarklets for iOS: https://www.cultofmac.com/500532/how-to-add-bookmarklet-mobile-iphone-safari/

In order to get Facebook Messenger to work in Safari on iOS, you'll need to set it to always request the desktop site on [messenger.com](https://messenger.com). 

When you visit the site on your phone now, just tap the bookmarklet to improve the mobile usability of Facebook Messenger in Safari. 
