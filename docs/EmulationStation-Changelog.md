This page is a list of all of the changelogs for each version of EmulationStation. For a complete list of all commits to 
the source code see [here](https://github.com/RetroPie/EmulationStation/commits/master):

* Latest (Dev)
  * [BUGFIX](https://github.com/RetroPie/EmulationStation/pull/364): Fix size of snapshot for `md_video` when using `<size>` theme option.
  * [BUGFIX](https://github.com/RetroPie/EmulationStation/pull/363): Fix scraper for Game & Watch.
  * [BUGFIX](https://github.com/RetroPie/EmulationStation/pull/362): Fix to properly allow `md_video` snapshot to display a different image then `md_image`.
  * [ENHANCEMENT](https://github.com/RetroPie/EmulationStation/pull/353): New horizontal wheel type for System View carousel.
  * [BUGFIX](https://github.com/RetroPie/EmulationStation/pull/351): Fix filters not updating properly after creating first favorite.
  * [NEW FEATURE](https://github.com/RetroPie/EmulationStation/pull/348): Rotate Screen support.
  * [ENHANCEMENT](https://github.com/RetroPie/EmulationStation/pull/337): Improved performance when fetching MAME names.
  * [BUGFIX](https://github.com/RetroPie/EmulationStation/pull/334): Fix VLC not muting audio after first loop.
  * [NEW FEATURE](https://github.com/RetroPie/EmulationStation/pull/324): Custom Viewport support.
* 2.7.4 (Stable)
  * [BUGFIX](https://github.com/RetroPie/EmulationStation/pull/323): Fix crash when removing last entry in favorites.
* 2.7.2
  * [NEW FEATURE](https://github.com/RetroPie/EmulationStation/pull/292): CEC support.
* 2.7.1
  * [ENHANCEMENT](https://github.com/RetroPie/EmulationStation/pull/283): Improved title scrolling in gamelist.
  * [BUGFIX](https://github.com/RetroPie/EmulationStation/pull/287): Fix for video screensaver when menu is open.
* 2.7.0
  * [ENHANCEMENT](https://github.com/RetroPie/EmulationStation/pull/282): Enable Jump to letter when gamelist is filtered.
  * [NEW FEATURE](https://github.com/RetroPie/EmulationStation/pull/252): Support for file filtering and hiding systems via Kids Mode.
  * [ENHANCEMENT](https://github.com/RetroPie/EmulationStation/pull/257): Option to launch directly to a gamelist vs. system view.
  * [ENHANCEMENT](https://github.com/RetroPie/EmulationStation/pull/266): Support for default paths to game image/video.
* 2.6.5
  * [ENHANCEMENT](https://github.com/RetroPie/EmulationStation/pull/256): Default image paths in themes.
  * [ENHANCEMENT](https://github.com/RetroPie/EmulationStation/pull/255): Normalize volume level for OMX player.
  * [NEW FEATURE](https://github.com/RetroPie/EmulationStation/pull/235): Kiosk Mode allows certain menu items.
* 2.6.4
  * [BUGFIX](https://github.com/RetroPie/EmulationStation/pull/246): Fix scrolling bug when using Power Saver.
* 2.6.3 (RetroPie 4.3)
  * [NEW FEATURE](https://github.com/RetroPie/EmulationStation/pull/207): Image slideshow screensaver. 
* 2.6.2
  * [ENHANCEMENT](https://github.com/RetroPie/EmulationStation/pull/226): Adjust menu widths to be dependent on lesser of two dimensions.
  * [BUGFIX](https://github.com/RetroPie/EmulationStation/pull/226): Fix bug causing crash when entering gamelist on some platforms.
* 2.6.1
  * [BUGFIX](https://github.com/RetroPie/EmulationStation/pull/225): System Carousel now properly renders when only one system is present.
  * [ENHANCEMENT](https://github.com/RetroPie/EmulationStation/pull/222): Swap time for Video Screensaver now configurable in settings menu.
  * [BUGFIX](https://github.com/RetroPie/EmulationStation/pull/221): Fix blank screen occurring when exit game animation is interrupted by key press.
  * [ENHANCEMENT](https://github.com/RetroPie/EmulationStation/pull/220): Volume setting now controls video volume when using OMX player.
  * [ENHANCEMENT](https://github.com/RetroPie/EmulationStation/pull/212): Carousel enhancements
    - Size and opacity of logos are now animated and transition smoothly when scrolling.
    - Origin now supported for `<carousel>` theme element.
    - Support for new vertical wheel carousel type.
    - BUGFIX: Text logos now increase in size properly.
    - BUGFIX: Background extras and logos no longer bleed into gamelists when using vertical carousel.
* 2.6.0
  * [NEW FEATURE](https://github.com/RetroPie/EmulationStation/pull/210): Custom Game Collections
  * [ENHANCEMENT](https://github.com/RetroPie/EmulationStation/pull/195): Theme enhancements
    - Origin now supported for `<text>`, `<rating>` and `<textlist>` theme elements.
    - Rotation support added for `<image>`, `<text>`, `<rating>`, and `<video>` theme elements.
* 2.5.2
  * [BUGFIX](https://github.com/RetroPie/EmulationStation/pull/202): Fix screensaver not triggering when using PowerSaver
  * [BUGFIX](https://github.com/RetroPie/EmulationStation/pull/199): Various bugfixes and enhancements for PowerSaver.
* 2.5.1
  * [BUGFIX](https://github.com/RetroPie/EmulationStation/pull/192): Fixed default font sizes when running in vertical orientation.
* 2.5.0
  * [NEW FEATURE](https://github.com/RetroPie/EmulationStation/pull/183): Added option to hide *nix hidden files.
  * [NEW FEATURE](https://github.com/RetroPie/EmulationStation/pull/172): Implemented Power Saver feature.
* 2.4.1
  * [BUGFIX](https://github.com/RetroPie/EmulationStation/pull/180): Fixed bug with random game selection.
* 2.4.0
  * [NEW FEATURE](https://github.com/RetroPie/EmulationStation/pull/168): Game Collections: Currently supports "All", "Favorites" and "Last Played" systems.
  * [BUGFIX](https://github.com/RetroPie/EmulationStation/pull/178): Moved slider menu items back to the top of menu to work around bug affecting some users.
  * [ENHANCEMENT](https://github.com/RetroPie/EmulationStation/pull/177): Fix for lack of zoom transition on video view for systems without marquees.
  * [NEW FEATURE](https://github.com/RetroPie/EmulationStation/pull/173): Variable support for themes.
    - Themes can now define and reference variables. ([docs](https://github.com/RetroPie/EmulationStation/blob/master/THEMES.md#theme-variables))
    - Themes can now define a default theme that will be used for any systems that the theme does not explicitly support.
 ([tutorial](EmulationStation-Advanced-Theming#default-theme))
    - Additional Theme options available for logoText element on System and Gamelist views.
  * [ENHANCEMENT](https://github.com/RetroPie/EmulationStation/pull/170): Carousel sliding transition can now be disabled.
  * [ENHANCEMENT](https://github.com/RetroPie/EmulationStation/pull/175): Returned 'JUMP TO LETTER' option back to top of menu.
* 2.3.2
  * [BUGFIX](https://github.com/RetroPie/EmulationStation/pull/169): Fixed gamelist sizing by using max of computed size vs set size
* 2.3.1
  * [BUGFIX](https://github.com/RetroPie/EmulationStation/pull/162): Fixed show snapshot on delay option for video element.
  * [BUGFIX](https://github.com/RetroPie/EmulationStation/pull/161): Fixed default color for rating component
* 2.3.0
  * [NEW FEATURE](https://github.com/RetroPie/EmulationStation/pull/153): Adding Random Video Screensaver/Attract Mode
  * [ENHANCEMENT](https://github.com/RetroPie/EmulationStation/pull/159): Make color themable for ratings like image component.
  * [BUGFIX](https://github.com/RetroPie/EmulationStation/pull/157): Game names are no longer cut off in gamelist when using `horizontalMargin` option.
  * [BUGFIX](https://github.com/RetroPie/EmulationStation/pull/157): Selector bar now lines up properly when using `lineSpacing` option.
  * [ENHANCEMENT](https://github.com/RetroPie/EmulationStation/pull/157): Added additional theme options for gamelist to provide better control over rendering of the selector bar.
  * [ENHANCEMENT](https://github.com/RetroPie/EmulationStation/pull/): Fixes for USB sound cards
      - Ability to change device used for Volume control (PCM/Speaker/Master) only on Pi.
      - Ability to change Audio device used for OMX player (local/hdmi/both/ALSA:HW:0,0/ALSA:HW:1,0)
* 2.2.1
  * [BUGFIX](https://github.com/RetroPie/EmulationStation/pull/154): Fixed broken zoom launch transition.
* 2.2.0
  * [NEW FEATURE](https://github.com/RetroPie/EmulationStation/pull/149): Added Instant transition.
  * [NEW FEATURE](https://github.com/RetroPie/EmulationStation/pull/74): Allow configuring the "hotkey enable" button
  * [ENHANCEMENT](https://github.com/RetroPie/EmulationStation/pull/146): Help Component now maintains styling from theme when in menus.
  * [BUGFIX](https://github.com/RetroPie/EmulationStation/pull/150): Prevent views from overflow onto an adjacent view.
    - use clip rects to prevent views overflow onto other views
  * [ENHANCEMENT](https://github.com/RetroPie/EmulationStation/pull/143): Scaper is no longer blocks UI rendering and properly shows the busy animation.
  * [BUGFIX](https://github.com/RetroPie/EmulationStation/pull/148): Fixed image stretch in video component.
  * [ENHANCEMENT](https://github.com/RetroPie/EmulationStation/pull/): Adding OMX Player option on RPI for improved video rendering.
  * [BUGFIX](https://github.com/RetroPie/EmulationStation/pull/145): Fixed Game Count display in System View when system is filtered.
  * [BUGFIX](https://github.com/RetroPie/EmulationStation/pull/142): Fixed default z-index values for metadata fields on detail view.
  * [ENHANCEMENT](https://github.com/RetroPie/EmulationStation/pull/140): Added new platforms to scraper
* 2.1.9
  * [ENHANCEMENT](https://github.com/RetroPie/EmulationStation/pull/139): Scrapper improvements.
    - Added FDS to scraper.
    - Added support to search for specific game id using id:###
  * [ENHANCEMENT](https://github.com/RetroPie/EmulationStation/pull/134): Slide transition will slide vertically for vertical carousel.
  * [ENCHANCEMENT](https://github.com/RetroPie/EmulationStation/pull/125): Added sorting options for the number of players, release date, genre, developer and publisher.
  * [ENHANCEMENT](https://github.com/RetroPie/EmulationStation/pull/52): Switch to new splashscreen with black background
  * [NEW FEATURE](https://github.com/RetroPie/EmulationStation/pull/130): z-index support allow themes to specify drawing order ([docs](https://github.com/RetroPie/EmulationStation/blob/master/THEMES.md#element-rendering-order-with-z-index))
  * [BUGFIX](https://github.com/RetroPie/EmulationStation/pull/129): Changes to mitigate white flashes in heavier themes
  * [BUGFIX](https://github.com/RetroPie/EmulationStation/pull/128): Fixed Scrapping PSP games.
* 2.1.8
  * [ENCHANCEMENT](https://github.com/RetroPie/EmulationStation/pull/108): Added menu option to explicitly choose the Gamelist type.
  * [NEW FEATURE](https://github.com/RetroPie/EmulationStation/pull/115): Added ability to filter gamelists by genre, players, ratings and publisher/developer.
* 2.1.7
  * [BUGFIX](https://github.com/RetroPie/EmulationStation/pull/122): Fix black boxes appearing on gamelist after scrolling
  * [NEW FEATURE](https://github.com/RetroPie/EmulationStation/pull/118): Added Go-to Random Game feature.
  * [ENHANCEMENT](https://github.com/RetroPie/EmulationStation/pull/109): Added support for additional metadata fields on folders.
  * [BUGFIX](https://github.com/RetroPie/EmulationStation/pull/116): Fixed bug where carousel theme fails to load under certain conditions.
* 2.1.6
  * [BUGFIX](https://github.com/RetroPie/EmulationStation/pull/112): Fix image ratio for first image in video game list view.
  * [NEW FEATURE](https://github.com/RetroPie/EmulationStation/pull/101): Added ability to theme the system carousel
* 2.1.5 (RetroPie 4.2)
  * [ENHANCEMENT](https://github.com/RetroPie/EmulationStation/pull/93): Fix initial text positioning and improve keyboard handling in TextEditComponent
  * [ENHANCEMENT](https://github.com/RetroPie/EmulationStation/pull/102): Added maxSize support for videos.
  * [ENHANCEMENT](https://github.com/RetroPie/EmulationStation/pull/94): Video view will no longer activate if the current theme does not support it.
  * [BUGFIX](https://github.com/RetroPie/EmulationStation/pull/99): Fix for Neo Geo games not being scraped.
* 2.1.4
  * [BUGFIX](https://github.com/RetroPie/EmulationStation/pull/88): Fix WSOD by loading textures on demand in a separate thread when a user configurable texture memory threshold is reached.
* 2.1.3
  * [NEW FEATURE](https://github.com/RetroPie/EmulationStation/pull/83): Added ability to disable the splashscreen.
* 2.1.2
  * [ENHANCEMENT](https://github.com/RetroPie/EmulationStation/pull/78): Improve Shutdown time by only writing changes to gamelist.xml.
* 2.1.1
  * [BUGFIX](https://github.com/RetroPie/EmulationStation/pull/79): Fix crash when saving metadata.
* 2.1.0
  * [NEW FEATURE](https://github.com/RetroPie/EmulationStation/pull/): Added video view to allow video preview of games in gamelist
