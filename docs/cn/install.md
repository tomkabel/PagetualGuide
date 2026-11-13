# 安装指南
## 1 脚本管理器 - 3秒
东方永页机基于油猴插件，因此需要一个脚本管理器以运行脚本。
::: details 💡 Q：什么是“浏览器油猴脚本”？
A：“油猴”是一种在浏览器上运行和管理脚本的插件。所谓脚本就是一段代码，它们能够自定义网页的行为和外观，优化您的网页浏览体验。安装之后，有些脚本能为网站添加新的功能，有些能使网站的界面更加易用，有些则能隐藏网站上烦人的广告。
:::

::: details 💡 Q：为什么写成用户脚本而非浏览器扩展？
A：因为东方永页机具有强大的自定义代码执行能力，而扩展为了安全对自定义代码执行能力有所限制。此外，用户脚本更为灵活，可以运行于几乎任何操作系统上，例如 Windows / MAC / iOS / Android。
:::

::: details 💡 Q：用户脚本是否安全？
A：用户脚本本身并不具有恶意行为，但安全性取决于您选择安装的脚本。建议只从可信的源获取脚本，并仔细阅读脚本代码。
:::

::: details 💡 Q：如何安装用户脚本？
A：首先，您需要在浏览器上安装脚本管理器插件（如Tampermonkey）。然后，您可以在插件管理界面中安装和管理用户脚本。
:::

::: details 💡 Q：我可以在移动设备上使用用户脚本吗？
A：通常情况下，移动设备的默认浏览器不支持用户脚本。但一些特定浏览器提供相关功能的插件或扩展。
:::

::: details 💡 Q：如何禁用或删除用户脚本？
A：您可以在用户脚本插件管理界面中禁用或删除特定的油猴脚本。您还可以临时禁用整个脚本管理器插件，以停止所有脚本的运行。
:::

### 🛠️ 推荐脚本管理器

+ 桌面端
  - Microsoft Edge: [Tampermonkey](https://microsoftedge.microsoft.com/addons/detail/tampermonkey/iikmkjmpaadaobahmlepeloendndfphd) | [Violentmonkey](https://microsoftedge.microsoft.com/addons/detail/violentmonkey/eeagobfjdenkkddmbclomhiblgggliao)
  - Chrome: [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) | [Violentmonkey](https://chrome.google.com/webstore/detail/violent-monkey/jinjaccalgkegednnccohejagnlnfdag)
  - Firefox: [Greasemonkey](https://addons.mozilla.org/firefox/addon/greasemonkey/) | [Tampermonkey](https://addons.mozilla.org/firefox/addon/tampermonkey/) | [Violentmonkey](https://addons.mozilla.org/firefox/addon/violentmonkey/)
  - Safari: [Tampermonkey](http://tampermonkey.net/?browser=safari) | [Userscripts](https://apps.apple.com/app/userscripts/id1463298887)
  - Opera: [Tampermonkey](https://addons.opera.com/extensions/details/tampermonkey-beta/) | [Violentmonkey](https://violentmonkey.github.io/get-it/)
  - Maxthon: [Violentmonkey](http://extension.maxthon.com/detail/index.php?view_id=1680)
  - [AdGuard](https://adguard.com/)
+ 移动端 (安卓)
  - Firefox: [Greasemonkey](https://addons.mozilla.org/firefox/addon/greasemonkey/) | [Tampermonkey](https://addons.mozilla.org/firefox/addon/tampermonkey/) | [Violentmonkey](https://addons.mozilla.org/firefox/addon/violentmonkey/)
  - Maxthon: [Violentmonkey](http://extension.maxthon.com/detail/index.php?view_id=1680)
  - Dolphin: [Tampermonkey](https://play.google.com/store/apps/details?id=net.tampermonkey.dolphin)
  - UC: [Tampermonkey](https://www.tampermonkey.net/?browser=ucweb&ext=dhdg)
  - Kiwi: [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) | [Violentmonkey](https://chrome.google.com/webstore/detail/violent-monkey/jinjaccalgkegednnccohejagnlnfdag)
  - [XBrowser](https://www.xbext.com/)
+ 移动端 (iOS)
  - Safari: [Tampermonkey](http://tampermonkey.net/?browser=safari) | [Userscripts](https://apps.apple.com/app/userscripts/id1463298887)
  - [Gear](https://gear4.app/)

## 2 安装东方永页机 - 2秒
<div style="display: flex"><a style="transition: box-shadow .2s; display: inline-block; background-color: #e2510a; padding: 0.7rem 1.1rem; color: #fff; text-decoration: none; font-weight: 700; height: fit-content; margin: 6px 0 0 10px;" href="https://tomkabel.github.io/UserScripts/Pagetual/pagetual.user.js">Github 库</a></div>

## 3 安装之后
安装之后建议前往高级自定义页导入基础规则库，基础库针对诸多常用站点编写了规则。