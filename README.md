# Edge Translate

[![996.icu](https://img.shields.io/badge/link-996.icu-red.svg)](https://996.icu)

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/EdgeTranslate/EdgeTranslate/blob/master/LICENSE.MIT)
[![License](https://img.shields.io/badge/License-NPL%20(The%20996%20Prohibited%20License)-blue.svg)](https://github.com/EdgeTranslate/EdgeTranslate/blob/master/LICENSE.NPL)

[![Version](https://img.shields.io/github/release/EdgeTranslate/EdgeTranslate.svg?label=version)](https://github.com/EdgeTranslate/EdgeTranslate/releases)
[![Build Status](https://travis-ci.com/EdgeTranslate/EdgeTranslate.svg?branch=master)](https://travis-ci.com/github/EdgeTranslate/EdgeTranslate)
[![codebeat badge](https://codebeat.co/badges/901b9567-d213-48cc-a4f3-200339c59705)](https://codebeat.co/projects/github-com-edgetranslate-edgetranslate-master)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FEdgeTranslate%2FEdgeTranslate.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2FEdgeTranslate%2FEdgeTranslate?ref=badge_shield)

[![Chrome Web Store](https://badgen.net/chrome-web-store/users/bocbaocobfecmglnmeaeppambideimao?icon=chrome&color=green)](https://chrome.google.com/webstore/detail/bocbaocobfecmglnmeaeppambideimao?hl=en)
[![Chrome Web Store](https://badgen.net/chrome-web-store/stars/bocbaocobfecmglnmeaeppambideimao?icon=chrome&color=green)](https://chrome.google.com/webstore/detail/bocbaocobfecmglnmeaeppambideimao?hl=en)
[![Mozilla Add-on](https://badgen.net/amo/users/edge_translate?icon=firefox&color=green)](https://addons.mozilla.org/firefox/addon/edge_translate/)
[![Mozilla Add-on](https://badgen.net/amo/stars/edge_translate?icon=firefox&color=green)](https://addons.mozilla.org/firefox/addon/edge_translate/)

View this page in other languages:

* [简体中文](./docs/README_CN.md)

* [繁體中文](./docs/README_TW.md)

## Demo

![demo_en](./docs/images/demo_en.gif)

## Downloads

[Microsoft Edge Add-ons](https://microsoftedge.microsoft.com/addons/detail/bfdogplmndidlpjfhoijckpakkdjkkil)
/ [Chrome Web Store](https://chrome.google.com/webstore/detail/bocbaocobfecmglnmeaeppambideimao)
/ [Firefox Add-ons](https://addons.mozilla.org/firefox/addon/edge_translate/)
/ [QQ Browser Web Store](https://appcenter.browser.qq.com/search/detail?key=edgetranslate&id=bocbaocobfecmglnmeaeppambideimao%20&title=edgetranslate)
/ [360 Browser Web Store](https://ext.se.360.cn/webstore/detail/jkhojcaggkaojlhfddocjkkphfdkejeg)

__Attention:__ The version in Firefox Add-ons does not support page translate anymore. If you need page translate, please refer to [here](./docs/wiki/en/ToFirefoxUsers.md).

## Manually Install

Firstly you need to download the extension package for your browser (Chrome and QQ Browser use the same package) from [GitHub Releases](https://github.com/EdgeTranslate/EdgeTranslate/releases).

It is always recommended to download the latest version.

### Chrome

* Extract the `.zip` package to somewhere on your disk.

* Navigate to: `chrome://extensions`.

* Enable `Developer mode`. It should be in the upper right corner of the page.

* Click `Load unpacked` in the upper left corner.

* Navigate to the directory of the extracted package.

### QQ Browser

* Extract the `.zip` package to somewhere on your disk.

* Navigate to: `qqbrowser://extensions/manage`.

* Enable `Developer mode`. It should be in the upper right corner of the page.

* Click `Load unpacked` in the upper left corner.

* Navigate to the directory of the extracted package.

### Firefox

* Installation will start automatically after the `.xapi` package is downloaded through Firefox browser.

### 360 Browser

* Right click on the package file and choose "Use 360 Browser to open", then it will be installed automatically.

## Build It By Yourself

To build the extension, you need to have [Node.js](https://nodejs.org/) installed.

Clone the repository:

```shell
git clone https://github.com/EdgeTranslate/EdgeTranslate.git
```

Install dependencies:

```shell
npm install
```

Build Chrome version:

```shell
npm run build:chrome
```

Build Firefox version:

```shell
npm run build:firefox
```

After building finished, you will get the unpacked extension under `./build/chrome/` and `./build/firefox/`.

## Load Unpacked Extension In Your Browser

### Chrome

* Navigate to: `chrome://extensions`.

* Enable `Developer mode`. It should be in the upper right corner of the page.

* Click `Load unpacked` in the upper left corner.

* Navigate to the repository you just cloned, select `build/chrome`.

* Now you can try this extension in Chrome.

### Firefox

* Navigate to: `about:debugging`.

* Check the `Enable add-on debugging` box if it's not checked.

* Click `Load Temporary Add-on`.

* Navigate to the repository you just cloned, open `build/firefox`, select any file in this directory.

* Now you can try this extension in Firefox.

## More Information

[Wiki](./docs/wiki/en/Introduction.md)

## Contact Us

E-mails: [nickyc975](mailto:chenjinlong2016@outlook.com), [Mark Fenng](mailto:f18846188605@gmail.com)

Telegram channel: [Edge Translate Channel](https://t.me/EdgeTranslate)

QQ group: [Edge Translate QQ Group](https://jq.qq.com/?_wv=1027&k=gT5EYfFB)

Join the channel or group to get Edge Translate beta packages before releases.

## License

[MIT](./LICENSE.MIT) AND [NPL](./LICENSE.NPL)

## Contributors

* [Yang, Bo](https://github.com/Atry)

* [ArielAxionL](https://github.com/axionl) 

* [ElectroLom](https://github.com/electrolom42)

* [knlyknly](https://github.com/knlyknly)

* [ykyuki](https://github.com/ykyuki)

* [Isildur46](https://github.com/Isildur46)

## Help Localization

If you want to help localize Edge Translate, please read the following guide.

[Localization](./docs/wiki/en/Localization.md)

## Sponsor

It took us much time and energy to develop this project. If it truly helped you in some way, you could reward us with cans of Coke to support us to keep improving it: [PayPal](https://paypal.me/EdgeTranslate).

But, this is completely __voluntary__. Sponsoring won't bring any special treatment and you can still use Edge Translate freely without sponsoring. Do it according to your capability!
