# BetterDiscord-Embeds

A plugin for Better Discord that allows you to send fancy embed messages like this

![Embed Example](https://raw.githubusercontent.com/Fraserbc/BetterDiscord-Embeds/master/images/embed_example1.PNG)

# Disclaimer!
## It is possible that Discord will ban and delete your account for using this plugin
I can not be held responsible if this happens.

# Installation
* Clone this repository
* Copy SendEmbeds.plugin.js to your plugins folder, you can acces this by going into your user settings, plugins and clicking "Open Plugin Folder"

# Usage
```
    /e title:           Your title
    description:        Your description
    url:                The url your title sends you to when you click it
    color:              The hex color code of the embed
    timestamp:          True or False - If you want a timestamp at the bottom of your embed or not
    footer_image:       The url of the image in the footer
    footer:             The footer text
    thumbnail:          The url of the thubmnail image
    image:              The url of the main image
    author:             The name of the author
    author_url:         The url clicking the authors name send you to
    author_icon:        The url of the author's icon
```

The title should be enclosed in double quotes and there needs to be a `#` infront of the color code

Here's an example:

```
/e title: My cool title
description: Cool embeds
url: https://discordapp.com
color: #1243ff
timestamp: true
footer_image: https://cdn.discordapp.com/embed/avatars/0.png
footer: WOW! Footers!
thumbnail_image: https://cdn.discordapp.com/embed/avatars/0.png
image_url: https://cdn.discordapp.com/embed/avatars/0.png
author: ABCD
author_url: https://discordapp.com
author_icon: https://cdn.discordapp.com/embed/avatars/0.png
```

# FAQ

## How do I do multiline embeds?

~~The same way you do it normally with `Shift + Enter`~~

The current update has broken this functionality. This will be fixed a some point in the future

## It's not working and I don't know why!?

Try installing this plugin https://github.com/samogot/betterdiscord-plugins/tree/master/v2/1Lib%20Discord%20Internals

And if that fails, create an issue with all the detail you can and I will respond as soon as possible

# Credit

I would like to give credit to Septeract, https://github.com/hepteract/, as he originally wrote the code this is based off. Here is the original gist for anyone interested.

https://gist.github.com/hepteract/8d9199a6a154dd32a1c4ced97de76043

Come visit me on discord! DeltaDeveloper#5381