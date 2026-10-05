On linux, the Firefox config `widget.gtk.ignore-bogus-leave-notify` might need to be set to `1` to prevent the sideabar from hiding when dragging tabs. See https://github.com/MrOtherGuy/firefox-csshacks/issues/577
```css
/* From https://github.com/Shina-SG/Shina-Fox */
/*** hover effects ***/
@media screen and (max-width: 40px) {
	#root {
    --tabs-indent: 0px;
	}
}

```
