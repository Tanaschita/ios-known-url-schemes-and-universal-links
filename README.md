# List of known iOS URL Schemes and Universal Links

## What is this?

This repository collects a list of known URL schemes and Universal Links supported by popular apps.

The list is sorted alphabetically.

**URL Scheme** - used to launch a specific app from another app on the user's iOS device. If the app is not installed, it will show an error message.

**Universal Link** - also used to launch a specific app from another app on the user's iOS device. If the app is not installed, the link will open in user's browser.

## How to contribute?

If you are missing an application in the list or notice outdated information, feel free to create a Pull Request. Please only add applications with officially documented URL Schemes / Universal Links.

## Known iOS URL Schemes and Universal Links

- **App Store**
	- `https://itunes.apple.com/us/app/apple-store/id375380948?mt=8` to open a specific application in App Store
	- more information in the [official documentation](https://developer.apple.com/library/archive/qa/qa1629/_index.html )
- **FaceTime**
	- `facetime://` to open FaceTime
	- `facetime://user@example.com` to make a video call
	- `facetime-audio://user@example.com` to make an audio call
	- more information in the [official documentation](https://developer.apple.com/library/archive/featuredarticles/iPhoneURLScheme_Reference/FacetimeLinks/FacetimeLinks.html#//apple_ref/doc/uid/TP40007899-CH2-SW1)
- **Google Chrome** 
	- `googlechrome://github.com` to open a http url
	- `googlechromes://github.com` to open a https url
	- more information in the [official documentation](https://developer.chrome.com/multidevice/ios/links)
- **Google Maps**
	- `comgooglemaps://` to open Google Maps
	- `comgooglemaps://?center=40.765819,-73.975866&zoom=14` to open the map centered on given location at given zoom
	- more information in the [official documentation](https://developers.google.com/maps/documentation/urls/ios-urlscheme)
- **Instagram**
	- `instagram://app` to open Instagram
	- `instagram://camera` to open camera
	- `instagram://user?username=USERNAME` to open profile of specific user
	- more information in the [official documentation](https://www.instagram.com/developer/mobile-sharing/iphone-hooks/)
- **Mail**
	- `mailto://foo@example.com` to create a mail to a specific email address
	- `mailto://foo@example.com?cc=bar@example.com` to add a cc email address
	- `mailto://foo@example.com?subject=test&body=test` to add subject and body
	- more information in the [official documentation](https://developer.apple.com/library/archive/featuredarticles/iPhoneURLScheme_Reference/MailLinks/MailLinks.html#//apple_ref/doc/uid/TP40007899-CH4-SW1)
- **Maps** 
	- `http://maps.apple.com/` to open Maps 
	- `http://maps.apple.com/?q=vegan+restaurant` to search for a specific place
	- `http://maps.apple.com/?ll=30.269686,-97.759912` to show a certain place with a given latitude and longitude
	- more information in the [official documentation](https://developer.apple.com/library/archive/featuredarticles/iPhoneURLScheme_Reference/MapLinks/MapLinks.html#//apple_ref/doc/uid/TP40007899-CH5-SW1)
- **Phone**
	- `tel://phonenumber` to make a call
	- more information in the [official documentation](https://developer.apple.com/library/archive/featuredarticles/iPhoneURLScheme_Reference/PhoneLinks/PhoneLinks.html#//apple_ref/doc/uid/TP40007899-CH6-SW1)
- **Spotify**
	- `spotify://` or `https://open.spotify.com/` to open Spotify
 	- more information in the [official documentation](https://developer.spotify.com/documentation/general/guides/content-linking-guide/)
- **YouTube**
	- `http://www.youtube.com/` to open Youtube
	- `http://www.youtube.com/v/VIDEO_IDENTIFIER` to open a specific video
	- more information in the [official documentation](https://developer.apple.com/library/archive/featuredarticles/iPhoneURLScheme_Reference/YouTubeLinks/YouTubeLinks.html#//apple_ref/doc/uid/TP40007899-CH8-SW1)
- **WhatsApp**
	- `whatsapp://` to open WhatsApp
	- `whatsapp://send?text=Hello` to create a new chat with a prefilled message
	- more information in the [official documentation](https://faq.whatsapp.com/en/iphone/23559013)

