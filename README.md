# Lichess userstyle for OBS (better clocks for streaming)

Originally from ornicar. Remove everything but the clocks and usernames in lichess for a better and more consistent streaming layout.

![Example image of how it could look in OBS](https://i.imgur.com/6DhlZCK.png)

## Usage

1. Add a browser source in OBS. (1920x1080 or whatever your screen resolution is.)
2. Set the URL to the player (YOURSELF for example) you want to follow: https://lichess.org/@/[WRITEHEREYOURUSERNAME]/tv
3. Insert Custom CSS from lichess.betterclocks.obs.css
4. Click `OK`
5. Crop the browser source as you like in order to just capture the clocks. Example:

![Browser Source in OBS](https://i.imgur.com/8S9p7lx.png)

Additionally you can change the background color by replacing the hexadecimal number in the code.

## EXAMPLE FOR BLUE BACKGROUD COLOR:

```
body {
    background: #131e61 !important;
}

body.dark {
    background: #131e61 !important;
}
```
