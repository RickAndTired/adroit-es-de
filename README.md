# adroit-es-de

Adroit ES-DE Theme

by Rick

Variants: Grid Covers, Grid Logos, List, List No Art

Color Schemes: Dark, Light, Animated

Aspect Ratios: 16:9, 16:10, 4:3, 19.5:9, 21:9, 1:1

<hr/>

Grid Covers - Dark
![sample1](https://github.com/RickAndTired/adroit-es-de/assets/53553229/ad64ae99-8b46-44fb-a9df-e463a6cc755a)
List - Dark

Grid Covers - Light
![sample2](https://github.com/RickAndTired/adroit-es-de/assets/53553229/bd2389db-97f5-4102-b997-25d106bfbe8a)
List - Light

<hr/>

If you would like to change which type of image is shown on the Grid Logos variant you can edit line `428` in the `theme_grid.xml`

`<imageType>marquee,cover,titlescreen</imageType>` 

Replace with your choice of: marquee,cover,3dbox,physicalmedia,titlescreen,miximage,fanart,screenshot, or backcover

<hr/>

You can provide your own video or gif background for the Animated scheme

In `adroit-es-de/files/` - remove `background.jpg` and `background.mp4`

Place your own `background.mp4` or `background.gif` inside 

(If you use an mp4 - also include a screenshot of the first frame as `background.jpg`)

You can use a `background.mp4` with audio to get background music

You can enable the `background.mp4` audio by changing `<audio>false</audio>` to true - `theme_grid.xml` line `143` and `theme_list.xml` line `163`

Background music and game video audio do not play well together - if you want to keep the background music you can disable the game video audio in `theme_list.xml` line `345`

<hr/>

This work is licensed under CC BY-NC-SA 4.0. To view a copy of this license, visit http://creativecommons.org/licenses/by-nc-sa/4.0/

System Controllers from [ES-DE](https://gitlab.com/es-de/themes/system-controllers-outline)

Akashi Font Author: Ten by Twenty

SIL Open Font Licese v1.10

Background video by [Gam-Ol](https://pixabay.com/videos/element-joystick-joypad-line-cross-67116/) under the Pixabay Content License
