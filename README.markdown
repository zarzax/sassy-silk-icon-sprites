# SASSy Silk Icon Sprites 
## A SASS mixin for using the creative commons Silk Icons (16x16px) as an image sprite 

## Usage
This is for working with the sample [compass css] [compass_core_website] project.  The sass mixin is in the src/partials directory and the sprites in images/.  These can be used in any personal or commercial product under the [Creative Commons License][license].

You can also use the sprites and the CSS in your project.  There are cleanly named css classes that will apply the named icon to an image.

    $ (sudo) gem install compass
    $ git clone http://github.com/zarzax/sassy-silk-icon-sprites.git
    $ cd sassy-silk-icon-sprites
    $ compass watch
  
Open index.html in a web browser.

## Updates
All of the sprites have been updated to be vertically aligned and contain 40px padding between images.  This enables them to be used more flexibly in containers that are taller and wider than the 16x16px dimensions.  I find it much easier to use sprites in ExtJS toolbars for example as the old sprites were generated horizontally with little padding.

## Interesting Note
Another note is that I have found the max dimension of a png can only be around 32,000px.  This has to do with how Microsoft uses a 16bit unsigned integer to reference dimensions (PNGs use 32bit integers internally) of PNGs.  This is why the sets have been broken up into different sprites.

## Author
This sass mixin was written by [Mark Young] [zarzax_home].

## Credits
 - Silk Icons Set by Mark James  [http://famfamfam.com/] [famfamfam]
 - Silk Companion II by [damieng.com] [companion1]
 - Silk Companion II by [Cagintranet Web Design] [companion2]

## License
Released under a [creative commons Attribution 2.5 license] [license].

[compass_core_website]: http://github.com/chriseppstein/compass/tree/master/frameworks/compass
[license]: http://creativecommons.org/licenses/by/2.5/
[zarzax_home]: http://www.zarzax.com
[famfamfam]: http://famfamfam.com/
[companion1]: http://damieng.com/creative/icons/silk-companion-1-icons
[companion2]: http://www.cagintranet.com/archive/download-famfamfam-silk-companion-2-icon-pack/