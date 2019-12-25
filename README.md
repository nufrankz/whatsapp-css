# whatsapp-css
## The only fully real transparent theme for Whatsapp.

## Features

### Transparency.
*`Transparency`*
You can set the entire theme's color, or transparency. Just pick a RGBA value, and write down on `--background` variable and you're set!

### Colors.
*`Background color`, `Accent`, `Text`, `Link`, `Message Out Bubble`*
You can change colors for:
- Accent (notificacions bubbles, menu hover items, scrollbars)
- Background (in case you want just a color and not an image)
- Text
- Links (different from Text color)
- Message Out Bubble (Whatsapp makes just that difference in it's original style)

### Font Family.
*`Font`*
- Modern (Helvetica and other sans-serif)
- Times New Roman (Palatino Lynotype and other serif)
- Console (Lucida Console and other console fonts)
- Old Console (Courier new and other old console fonts)
- Custom Font (instructions here)

#### Custom Font.
*`Custom Installed Font*`*
For your own Custom Font, follow this steps:
- Have the font already installed on your system
- Open your font file and copy the *PostScript Name*
  - Windows
    - Go to `%WINDIR%/Fonts`
    - Right-click the font of your choice
    - In `Details` tab, copy `Title` value
  - MacOS
    - Open `Font Book` app
    - Select the font of your choice
    - Click in the `Info` icon on the top left
    - Copy the `PostScript Name` value
- On the Style page on Userstyles.org, select *Custom* on the *Font* dropdown
- Then paste the *Postscript Name* into *Custom Installed Font*

### Doodles bakground.
*`Doodles`*
Original Whatsapp doodles pattern background, they're set on top of any background image or color you choose.
In two flavors (black or white), or none.

### Privacy Mode.
*`Privacy Mode`*
It blurs everything I consider to be private. You have to mouse-over to see all of this elements:
- Avatars
- Emojis
- Chat list names
- Chat title (contact name)
- Photographs and videos
- Stickers
Plus attenuates font opacity.

### Fullscreen.
*`Fullscreen`*
Whatsapp shrinks chat div app on resolutions bigger than 1396 pixels wide. If you have more than 1396 pixels wide resolution, you can choose to set the app div to be fullscreen or boxed.

### Background Image.
*`Background Image`*
You can choose a real background image, that covers all the background.
And if you set Transparency on the *Background Color*, you can see it through the Whatsapp interface!
You can choose *Color* (then set your desired color on *Background Color*), Night Sky, Black or upload your own image.

Be sure to choose contrasted background/interface/fonts variables. I suggest to choose darker interface, and bright text colors. It can be any background you choose.

#### Background Blur.
*`Background Image Blur (in pixels)`*
You can choose background blur! in pixels ammount. This, helps legibility and gives greater enhancement to text and interface elements.

### Emoji Opacity.
*`Emoji Opacity`*
For better legibility, you can attenuate emojis on the emoji selector panel. Write a decimal between 0 and 1 to set it (0 full transparent, 1 full opaque).

## Installation
This style works with a User Styles Manager. Actually, the two most downloaded are:

[Stylus](https://github.com/stylus/stylus)
[Stylish](https://github.com/stylish-userstyles/stylish)

Both extensions works, and have differences, the main one, referring to [your privacy](https://robertheaton.com/2018/07/02/stylish-browser-extension-steals-your-internet-history/). Choose wisely.

### Mozilla Firefox
[Latest release](https://www.mozilla.org/firefox)
[Stylus](https://addons.mozilla.org/firefox/addon/styl-us/)
[Stylish](https://addons.mozilla.org/firefox/addon/stylish/)

### Google Chrome
[Latest release](https://www.google.com/chrome/)
[Stylus](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne)
[Stylish](https://chrome.google.com/webstore/detail/stylish-custom-themes-for/fjnbnpbmkenffdnngjfgmeleoegfcffe)

### Opera
[Latest release](https://www.opera.com/download)
[Stylus](https://addons.opera.com/extensions/details/stylus/)

### Edge
It seems you can install Chrome extensions through the [Edge Extension Kit](https://www.microsoft.com/p/microsoft-edge-extension-toolkit/9nblggh4txvb?rtc=1&activetab=pivot:overviewtab#), then download the Chrome extension and load into it. Reports says it works well.

