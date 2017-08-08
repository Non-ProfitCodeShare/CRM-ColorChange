# CRM-ColorChange
Allows for the changing of the color on the navigation bar in Blackbaud CRM.

1. Open the navbarback-template.xcf file in GIMP, and edit the layer with color to whichever color you'd like.
    a. Then click File -> Export As
    b. Save this as "navbarback.png" in the file type png.

2. Edit the file "bbui-ext-jquery-min.css"
    a. Do a find and replace
        1. Search for `<<NAVBARCOLOR>>`
        2. Replace with your color (ex. #000000 for black)

3. Copy these two files from your CRM install as a backup...
    a. C:\Program Files\Blackbaud\bbappfx\vroot\browser\webui\min\bbui-ext-jquery-min.css
    b. C:\Program Files\Blackbaud\bbappfx\vroot\browser\BBUI\assets\skins\webshell\images\navbarback.png

4. Copy your modified files to your CRM install...
    a. C:\Program Files\Blackbaud\bbappfx\vroot\browser\webui\min\bbui-ext-jquery-min.css
    b. C:\Program Files\Blackbaud\bbappfx\vroot\browser\BBUI\assets\skins\webshell\images\navbarback.png


5. Done
