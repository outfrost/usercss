# UserCSS

Custom website styles for use with [Stylus](https://github.com/openstyles/stylus) (or any other UserCSS browser extension)

To install a style, simply click on the "Install directly with Stylus" button. It should work instantly with other extensions too, but in case it doesn't, you can copy the displayed code and paste it into an "Import" window or a new style in your preferred UserCSS manager.

You will receive style updates automatically, as long as your UserCSS manager supports them.

## Styles
### [Twitch player resolution fix](twitch-player-resolution-fix.user.css)

[![Install directly with Stylus](https://img.shields.io/badge/Install%20directly%20with-Stylus-00adad.svg)](https://raw.githubusercontent.com/outfrost/usercss/master/twitch-player-resolution-fix.user.css) [![Updates automatically](https://img.shields.io/badge/updates-automatically-882288.svg)](https://raw.githubusercontent.com/outfrost/usercss/master/twitch-player-resolution-fix.user.css)

Stops unwanted upscaling of stream video feeds by adjusting the width of other page elements (specifically, the navigation sidebar that shows your followed channels and friends).

In a maximised browser window, on a 2560x1440 display, provides a 1920x1080 stream player (1:1 resolution for most 1080p streams). On a 1920x1080 display, provides a 1280x720 stream player (1:1 resolution for most 720p streams). Thanks to this, you can now have a perfectly crisp video feed (and still see chat!) if the stream you're watching matches one of these common resolutions.

Check if it works correctly for you by clicking the cog icon in the stream player, going to "Advanced" and turning on "Video stats". "Display resolution" should be one of those mentioned above. Please report any errors in [issues](https://github.com/outfrost/usercss/issues).

### [Steam Workshop layout fixes](steam-workshop-fixes.user.css)

[![Install directly with Stylus](https://img.shields.io/badge/Install%20directly%20with-Stylus-00adad.svg)](https://raw.githubusercontent.com/outfrost/usercss/master/steam-workshop-fixes.user.css) [![Updates automatically](https://img.shields.io/badge/updates-automatically-882288.svg)](https://raw.githubusercontent.com/outfrost/usercss/master/steam-workshop-fixes.user.css)

A few fixes for annoying issues and sloppy designs in parts of the Steam Workshop page layout.

* Fixes subscribe buttons next to items in Workshop collections phasing into another dimension
* Makes the item list in collection edit mode a bit taller, so you don't have to second guess whether you've scrolled too far
Please report any errors in [issues](https://github.com/outfrost/usercss/issues).

## Contributing

Pull requests open. Please thoroughly explain any changes submitted. [Issues](https://github.com/outfrost/usercss/issues) are a good place to talk about bugs and development.
