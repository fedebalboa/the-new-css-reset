# The New CSS Reset

This new CSS reset is using the new CSS reset powers we got with the new global CSS reset keywords, 'unset' and 'revert' keywords, and with the new property of 'all' which can reset all properties combined.

[Download the Latest Version](https://raw.githubusercontent.com/elad2412/the-new-css-reset/main/css/reset.css)

## How it Looks and Works
```
/*** The new CSS Reset - version 1.0.0 (last updated 28.4.2021) ***/

/* Remove all the styles of the "User-Agent-Stylesheet",
   except for the 'display' property */
*:not(iframe, canvas, img, svg video):not(svg *){
    all: unset;
    display: revert;
}

/* Preferred box-sizing value */
*,
*::before,
*::after{
    box-sizing: border-box;
}

/* Remove list styles (bullets/numbers) */
ol, ul {
    list-style: none;
}

/* For images to not be able to exceed their container */
img {
    max-width: 100%;
}

/* removes spacing between cells in tables */
table{
    border-collapse: collapse;
}

```
## Extensive Reading and Watching
- [Understanding the “Initial”, “Inherit” and “Unset” CSS Keywords](https://elad.medium.com/understanding-the-initial-inherit-and-unset-css-keywords-2d70b7121695)
- [How Does CSS Work?](https://elad.medium.com/how-does-css-work-92fe7116916d)
- [The CSS Keywords That No One Really Understands (Video)](https://www.youtube.com/watch?v=nnhUBRRhKW0)