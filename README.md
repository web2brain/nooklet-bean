# Bean Nooklet
Did you ever have the problem that the brewing recipes for espresso are only available on your cellphone, where you have the possibility to use [Beanconqueror](https://github.com/graphefruit/Beanconqueror), but not displayed prominently in the kitchen? And where you also wondering what to do with your old [nook](https://en.wikipedia.org/wiki/Barnes_%26_Noble_Nook_1st_Edition), that you bought at Barnes & Noble ages ago?  

No? Then there's nothing to see here, please move along.  

Otherwise: this is a small nooklet displaying the brewing recipe for a coffee bean on the nook, that can be placed in the kitchen.

## Prerequisites
* A [nook](https://en.wikipedia.org/wiki/Barnes_%26_Noble_Nook_1st_Edition).
* Root the [nook](https://en.wikipedia.org/wiki/Barnes_%26_Noble_Nook_1st_Edition), details can be found at https://github.com/web2brain/nook-revival/.
* Install the [Nooklet APK](https://github.com/web2brain/nook-revival/blob/master/apks/nooklet.apk).
* Add this nooklet and add your own brewing information.
* A passion for coffee might help for a sensible usage. :coffee:

## Usage
1. Copy the files from `nooklet` to the folder `Nooklets` on your nook.
1. Change the name of the folder `Bean` to the name of your bean. The folder name will be the name of the nooklet and also the title for the brewing recipe.
1. Adjust the file [bean.js](Beans/bean.js) in the folder of your bean, adjusting the values to your settings.
1. Enjoy brewing delicious coffee! :coffee:

## Hints
- The css file is located in the root of the nooklets folder so that it can be changed for all beans at once.
- Currently the text is only in German, but that might be changed...
- "Bean" really refers to a coffee bean :-).
- Use `adb push` to update the `bean.js` wirelessly. More advanced automation will have to be investigated (I'd love a webhook from [Beanconqueror](https://github.com/graphefruit/Beanconqueror) when I mark a brew as "best brew").