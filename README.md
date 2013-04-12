![A gif-in-action](https://f.cloud.github.com/assets/846194/373560/14e80be6-a384-11e2-9905-713713798aaa.gif)

## Chrome New Tab Timezones

Because you're so cultured, right?

### On the Chrome Web Store

Go to the [Chrome Web Store](https://chrome.google.com/webstore/detail/new-tab/adcpijkmbecohfalcbafjgadfnpchhlg) and choose "Add to Chrome". Then you'll have it. Shaboom.

### Local Installation
`git clone` this repo. Go to Chrome Settings > Extensions ([chrome://extensions](chrome://extensions)). Choose "Load unpacked extension" and choose the `unpacked-extension` folder in this repo. Disable the extension to switch back to the original Chrome New Tab page.

### Customization

Install locally and change or add to the list in `newtab.html`:

```html
<li><span class="time" data-utc-offset="-7">&nbsp;</span><span class="location"> in San Francisco</span></li>
```

Change the city name and `data-utc-offset`, or add a new `<li>` with the same.

### Credit

Based on [adamschwartz](https://github.com/tech-no-crat)'s [chrome-new-tab](https://github.com/tech-no-crat/chrome-newtab-minimalism) who based his newtab page on [tech-no-crat](https://github.com/tech-no-crat)'s [chrome-newtab-minimalism](https://github.com/tech-no-crat/chrome-newtab-minimalism).

*How deep does the credit go??!*
