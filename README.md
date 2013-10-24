gimp-android-xdpi
=================
Update
======
Forked from https://github.com/ncornette/gimp-android-xdpi
I hacked this GIMP python script and added support for xxhdpi. I think it works :-) 
https://github.com/gywst/gimp-android-xdpi

Gimp plugin to export images or icons for all android densities. Just select the area to export, then run the plugin
from Filters/Android/Write Android XDPIs... Images will be written to your drawable-ldpi / mdpi / hdpi / xhdpi folders.
You can select a custom target width so you don't have to resize your picture.

To write you app icon directly from you full size picture, use these parameters : 

[![](https://lh5.googleusercontent.com/9ovI_ry3awmPs0tWjt2b08c5ykQxwFz7GQgltRxs3BOV5LREYr4pWPrMNunrZDeP5zCqig1kjiUmnd5-CmXzCNk_oKPTRC5i_qpbZBI_cazA29VC4dw)](https://lh5.googleusercontent.com/9ovI_ry3awmPs0tWjt2b08c5ykQxwFz7GQgltRxs3BOV5LREYr4pWPrMNunrZDeP5zCqig1kjiUmnd5-CmXzCNk_oKPTRC5i_qpbZBI_cazA29VC4dw) [![](https://lh6.googleusercontent.com/Tnh-CBdaOfsjZ5myoLH96zS4Akn_GvZbdIDRCT3p4gsk7Bp1nnCMQCJ_YlLjg-beorcq94UtSiv4UJfWRx6a7W-1Q2YlI68m_psy6VDADHMd7c-Svlc)](https://lh6.googleusercontent.com/Tnh-CBdaOfsjZ5myoLH96zS4Akn_GvZbdIDRCT3p4gsk7Bp1nnCMQCJ_YlLjg-beorcq94UtSiv4UJfWRx6a7W-1Q2YlI68m_psy6VDADHMd7c-Svlc)


 1. select your app res folder
 2. type `icon` as the image base name
 3. select a image width of `48`
 4. select a density of `mdpi`
 5. select image format `png`

Icon or Image resources for all densities will be scaled and written accordingly.
You will be warned if an image has been upscaled

[![](https://lh6.googleusercontent.com/LT7vn7uo2jmjul4ejuu59iM4elDto1TsjagX1Zp5wdgzPghQ_TBsUKGOF65y7m6XwW2DaTpJlxS2GxU9Xi3jklrxj2bR8c6d8blc6dgi8Iwnri56SlM)](https://lh6.googleusercontent.com/LT7vn7uo2jmjul4ejuu59iM4elDto1TsjagX1Zp5wdgzPghQ_TBsUKGOF65y7m6XwW2DaTpJlxS2GxU9Xi3jklrxj2bR8c6d8blc6dgi8Iwnri56SlM)

### Installation: 
* Put this file into your gimp plugin directory, ie: ~/.gimp-2.6/plug-ins/gimpfu_android_xdpi.py
* Restart Gimp
* Run script via Filters/Android/Write Android XDPIs...
