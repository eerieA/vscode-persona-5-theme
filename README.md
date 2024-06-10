# Persona 5 dark theme

A dark theme based on color palette from Atlus' Persona 5 game.

## Preview

![preview image 1](https://live.staticflickr.com/65535/53780739191_3c4f39042e_h.jpg)

![preview image 2](https://live.staticflickr.com/65535/53780739196_96b9ae3bb1_h.jpg)

## (Optional) Activity bar background

With [APC Customize UI](https://marketplace.visualstudio.com/items?itemName=drcika.apc-extension) extension installed and enabled, insert these into your user `settings.json` to change to the accompanying activity bar background for this theme:

```
    "apc.stylesheet": {
        ".monaco-workbench .part.activitybar>.content": {
            "background-image": "url('https://64.media.tumblr.com/54d3fca992acbabb3441c57196add523/a9160834f5fb85d1-4e/s540x810/4a6181885debf3d273f152c6376e8bffb50c7e8d.pnj')",
            "background-size": "600%",
            "background-position": "left 5% bottom 10%", /*Adjust as needed*/
            "background-blend-mode": "soft-light", /*Adjust as needed*/
            "background-repeat": "repeat",
            "background-color": "#585858", /*Adjust as needed*/
        },
        ".monaco-workbench .pane-composite-part>.header-or-footer": {
            "background-image": "url('https://64.media.tumblr.com/54d3fca992acbabb3441c57196add523/a9160834f5fb85d1-4e/s540x810/4a6181885debf3d273f152c6376e8bffb50c7e8d.pnj')",
            "background-size": "100%",
            "background-position": "left 0% bottom 40%", /*Adjust as needed*/
            "background-blend-mode": "soft-light", /*Adjust as needed*/
            "background-repeat": "no-repeat",
            "background-color": "#585858", /*Adjust as needed*/
        }
    }
```
The first style snippet is for activity bar on the left, and the second is for activity bar on the top and bottom.

![preview with activity bar background](https://live.staticflickr.com/65535/53781058824_a52715e1ad_h.jpg)