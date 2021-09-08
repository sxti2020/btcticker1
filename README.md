# Bitcoin price ticker for an old Android phone

This is a cheap alternative to the *LaMetric Time* as a price ticker. 
For the ones that don't want to spend $200, and repurpose an old Android device and do it for free.

It reads Binance bitcoin USD trade at real-time and updates screen every 3 seconds.

<img src="https://github.com/shibuyastarbucks/btc-ticker/blob/master/screenshot.png?raw=true" alt="screenshot" width="800"/>

It is best viewed in landscape mode. Tested on Moto G, it's the oldest that I did not throw away.

## Requirements
1. Internet connection 
2. An Android phone with power adapter, also runs Chrome
3. Install [Fullscreen Immersive by duna](https://play.google.com/store/apps/details?id=immersive.duna.com.immersivemode&hl=en) on the Play Store. It is to hide navigation bars on the device. You don't have to buy the app, the basic functions is enough to have it working nicely.
4. Paper clip to make a phone stand, using [DIY Phone Stand](https://www.instructables.com/id/Paper-Clip-Mobile-Phone-Stand-2min-0-Project/) guide.
5. Optional app [Keep Screen On](https://play.google.com/store/apps/details?id=eu.aboutall.android.tools.kepscreenon&hl=en) on the Play Store. It ensures the screen won't dim and sleep. In case the built-in keep screen awake behavior is overridden by the phone.

## Usages
Browse to https://shibuyastarbucks.github.io/btc-ticker/
After few seconds the price will start appearing and updates.

Be sure to touch the screen at least once after initial load and every manual refresh of the page, as it is using [NoSleep.js](https://github.com/richtr/NoSleep.js/) to keep screen on all the time. 

To convert the value into your own liking, e.g.: to Euro and/or to your hodl profile. Append the URL with hashtag '#' followed by a number. Do a page refresh afterwards.

`#0.92` for Euro value; `#1.932` for Euro value with 2.1btc as 0.92 * 2.1 = 1.932.

### Donations for Author
*33a8kGMAJgKeKFUGa2dVH2NTtwgAgH26on*
