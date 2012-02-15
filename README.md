# StormBeans, a PhpStorm theme for human beings

This is a **dark**, eye-friendly, distraction-free and **_color-consistent_** PhpStorm theme.   
It's been inspired by a [Grafikart's theme](http://www.grafikart.fr/ressources/netbeans/theme-netbeans-10) for the NetBeans IDE.

For now,**PHP**, **HTML**, **Javascript** and **CSS** color schemes are implemented. Other languages' scheme are derivated from PhpStrom's  *default* color scheme.

## Preview  

This is how StormBeans is rendered by PhpStorm 3.0.2 on an Ubuntu 11.10 installation.

![Preview](http://i.minus.com/iRa1JZMYjiviH.png)

## Installation

1. Download the [`build/StormBeans.jar`](https://github.com/MrMitch/StormBeans/blob/master/build/StormBeans.jar?raw=true) file from this repo.
2. Open PhpStorm
3. Go to **File > Import Settings...**
4. Browse to the `StormBeans.jar` file you just downloaded
5. When asked for the components you want to import, make sure the 'Color schemes' box is checked
    ![Check the box!](http://i.minus.com/ibtLxrEKLbnlaN.png)
6. Go to **File > Settings**
7. In the *IDE Settings* section, go to **Editor > Colors & Fonts** 
8. In the right part of the window, select `StormBeans` in the list and hit `Apply`
9. Enjoy!

## Notes


The default font used is `DejaVu Sans Mono` at size 11.  
It can be changed by modifying the [`src/colors/StormBeans.xml`](https://raw.github.com/MrMitch/StormBeans/master/src/colors/StormBeans.xml) file.  
Change the `value` attribute of the third option (with the `name` being `EDITOR_FONT_NAME`).  
For instance, let's say you are using a computer running Microsoft Windows (*it's OK, I won't judge you even if I think you should try [THAT](http://www.ubuntu.com)* :trollface:) and want to use the `Consolas` font, you should edit the line like so :   

```xml
<option name="EDITOR_FONT_NAME" value="Consolas" />
```

