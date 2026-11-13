---
sidebarDepth: 3
next: usage
head:
  - - meta
    - name: description
      content: Как добавить бесконечную прокрутку на сайт? Лучшие Greasemonkey скрипты для продуктивности
  - - meta
    - name: keywords
      content: авто пейджер, бесконечная прокрутка, автоматическая загрузка страниц, получение контента, автоматическая загрузка страниц
---
# Руководство по установке

<img src="https://s2.loli.net/2024/09/11/qeM1ZQjRXvaJnSf.gif" alt="pagetual install" width=740 height=524 />

## Менеджер скриптов
Pagetual основан на Greasemonkey, поэтому для его работы требуется менеджер скриптов.

### 🛠️ Примеры менеджеров скриптов

Make sure to enable Allow User Scripts for the MV3 version of extension.

<table>
  <tbody>
    <td>
      <details open>
        <summary style="cursor:pointer;">🖥️ Рабочий стол</summary>
        <ul>
          <li>Chrome: <a href="https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo">Tampermonkey</a> | <a href="https://chrome.google.com/webstore/detail/violent-monkey/jinjaccalgkegednnccohejagnlnfdag">Violentmonkey</a></li>
          <li>Firefox: <a href="https://addons.mozilla.org/firefox/addon/greasemonkey/">Greasemonkey</a> | <a href="https://addons.mozilla.org/firefox/addon/tampermonkey/">Tampermonkey</a> | <a href="https://addons.mozilla.org/firefox/addon/violentmonkey/">Violentmonkey</a></li>
          <li>Safari: <a href="http://tampermonkey.net/?browser=safari">Tampermonkey</a> | <a href="https://apps.apple.com/app/userscripts/id1463298887">Userscripts</a></li>
          <li>Microsoft Edge: <a href="https://microsoftedge.microsoft.com/addons/detail/tampermonkey/iikmkjmpaadaobahmlepeloendndfphd">Tampermonkey</a> | <a href="https://microsoftedge.microsoft.com/addons/detail/violentmonkey/eeagobfjdenkkddmbclomhiblgggliao">Violentmonkey</a></li>
          <li>Opera: <a href="https://addons.opera.com/extensions/details/tampermonkey-beta/">Tampermonkey</a> | <a href="https://violentmonkey.github.io/get-it/">Violentmonkey</a></li>
          <li>Maxthon: <a href="http://extension.maxthon.com/detail/index.php?view_id=1680">Violentmonkey</a></li>
          <li><a href="https://adguard.com/">AdGuard</a></li>
        </ul>
      </details>
    </td>
    <td>
      <details>
        <summary style="cursor:pointer;">📱 Мобильный (Android)</summary>
        <ul>
          <li>Firefox: <a href="https://addons.mozilla.org/firefox/addon/greasemonkey/">Greasemonkey</a> | <a href="https://addons.mozilla.org/firefox/addon/tampermonkey/">Tampermonkey</a> | <a href="https://addons.mozilla.org/firefox/addon/violentmonkey/">Violentmonkey</a></li>
          <li>Maxthon: <a href="http://extension.maxthon.com/detail/index.php?view_id=1680">Violentmonkey</a></li>
          <li>Dolphin: <a href="https://play.google.com/store/apps/details?id=net.tampermonkey.dolphin">Tampermonkey</a></li>
          <li>UC: <a href="https://www.tampermonkey.net/?browser=ucweb&ext=dhdg">Tampermonkey</a></li>
          <li>Kiwi: <a href="https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo">Tampermonkey</a> | <a href="https://chrome.google.com/webstore/detail/violent-monkey/jinjaccalgkegednnccohejagnlnfdag">Violentmonkey</a></li>
          <li><a href="https://www.xbext.com/">XBrowser</a></li>
        </ul>
      </details>
    </td>
    <td>
      <details>
        <summary style="cursor:pointer;">🍎 Мобильный (iOS)</summary>
        <ul>
          <li>Safari: <a href="http://tampermonkey.net/?browser=safari">Tampermonkey</a> | <a href="https://apps.apple.com/app/userscripts/id1463298887">Userscripts</a></li>
          <li><a href="https://gear4.app/">Gear</a></li>
        </ul>
      </details>
    </td>
  </tbody>
</table>


## Установить Pagetual
<div style="display: flex"><a style="transition: box-shadow .2s; display: inline-block; background-color: #e2510a; padding: 0.7rem 1.1rem; color: #fff; text-decoration: none; font-weight: 700; height: fit-content; margin: 6px 0 0 10px;" href="https://tomkabel.github.io/UserScripts/Pagetual/pagetual.user.js">Github</a></div>

::: details 💡 В: Что такое "скрипт Greasemonkey для браузера"?
О: "Greasemonkey" — это плагин, который запускает скрипты и управляет ими в браузере. Скрипт — это фрагмент кода, который оптимизирует ваш опыт просмотра веб-страниц. После установки некоторые скрипты добавляют новую функциональность на сайт, некоторые упрощают использование интерфейса сайта, а некоторые скрывают надоедливую рекламу на сайте.
:::

::: details 💡 В: Почему Pagetual написан как пользовательский скрипт, а не как расширение?
О: Потому что Pagetual обладает мощными возможностями выполнения пользовательского кода для реализации правил подкачки, а расширения имеют ограничения на возможности выполнения пользовательского кода по соображениям безопасности. Кроме того, пользовательские скрипты более гибки и могут работать практически на любой операционной системе, такой как Windows/MAC/iOS/Android.
:::

::: details 💡 В: Безопасны ли пользовательские скрипты?
О: Сами по себе пользовательские скрипты не являются вредоносными, но безопасность зависит от скриптов, которые вы решите установить. Рекомендуется получать скрипты только из надежных источников и внимательно читать код скрипта. И, конечно, вы можете доверять мне — я вношу вклад в сообщество открытого исходного кода уже десять лет.
:::

::: details 💡 В: Как установить пользовательский скрипт?
О: Сначала вам нужно установить плагин-менеджер скриптов (например, Tampermonkey) в свой браузер. Затем вы сможете устанавливать пользовательские скрипты и управлять ими в интерфейсе управления плагином.
:::

::: details 💡 В: Могу ли я использовать пользовательские скрипты на мобильных устройствах?
О: Как правило, стандартный браузер мобильных устройств не поддерживает пользовательские скрипты. Однако некоторые специфические браузеры предоставляют плагины или расширения с соответствующими функциями.
:::

::: details 💡 В: Как отключить или удалить пользовательские скрипты?
О: Вы можете отключить или удалить определенные скрипты Grease Monkey в интерфейсе управления плагином пользовательских скриптов. Вы также можете временно отключить весь плагин Script Manager, чтобы остановить выполнение всех скриптов.
:::