---
sidebarDepth: 3
head:
  - - meta
    - name: description
      content: Wie fügt man unendliches Scrollen zu einer Website hinzu? Die besten Greasemonkey-Skripte für Produktivität
  - - meta
    - name: keywords
      content: Auto Pager, unendliches Scrollen, Seitenladeautomatisierung, Inhaltsabruf, automatisches Laden von Seiten
---
# Installationsanleitung
## Skript-Manager
Pagetual basiert auf Greasemonkey, daher benötigt es einen Skript-Manager, um zu funktionieren.

![pagetual_install.gif](https://s2.loli.net/2024/09/11/qeM1ZQjRXvaJnSf.gif)

### 🛠️ Beispiel-Skript-Manager

<table>
  <tbody>
    <td>
      <details>
        <summary style="cursor:pointer;">🖥️ Desktop</summary>
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
        <summary style="cursor:pointer;">📱 Mobil (Android)</summary>
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
        <summary style="cursor:pointer;">🍎 Mobil (iOS)</summary>
        <ul>
          <li>Safari: <a href="http://tampermonkey.net/?browser=safari">Tampermonkey</a> | <a href="https://apps.apple.com/app/userscripts/id1463298887">Userscripts</a></li>
          <li><a href="https://gear4.app/">Gear</a></li>
        </ul>
      </details>
    </td>
  </tbody>
</table>

## Pagetual installieren
<div style="display: flex"><a style="transition: box-shadow .2s; display: inline-block; background-color: #e2510a; padding: 0.7rem 1.1rem; color: #fff; text-decoration: none; font-weight: 700; height: fit-content; margin: 6px 0 0 10px;" href="https://tomkabel.github.io/UserScripts/Pagetual/pagetual.user.js">Github</a></div>

::: details 💡 F: Was ist ein "Browser Greasemonkey-Skript"?
A: "Greasemonkey" ist ein Plugin, das Skripte im Browser ausführt und verwaltet. Ein Skript ist ein Stück Code, das Ihr Surferlebnis optimiert. Nach der Installation fügen einige Skripte neue Funktionen zur Website hinzu, einige machen die Benutzeroberfläche der Website einfacher zu bedienen, und einige blenden lästige Anzeigen auf der Website aus.
:::

::: details 💡 F: Warum ist Pagetual als Userscript und nicht als Erweiterung geschrieben?
A: Weil Pagetual leistungsstarke Möglichkeiten zur Ausführung benutzerdefinierter Codes hat und Erweiterungen Einschränkungen hinsichtlich dieser Möglichkeiten aus Sicherheitsgründen haben. Darüber hinaus sind Userscripts flexibler und können auf nahezu jedem Betriebssystem ausgeführt werden, z. B. Windows/MAC/iOS/Android.
:::

::: details 💡 F: Sind Userscripts sicher?
A: Userscripts selbst sind nicht böswillig, aber die Sicherheit hängt von den Skripten ab, die Sie installieren. Es wird empfohlen, Skripte nur aus vertrauenswürdigen Quellen zu beziehen und den Skriptcode sorgfältig zu lesen.
:::

::: details 💡 F: Wie installiert man ein Userscript?
A: Zuerst müssen Sie ein Skript-Manager-Plugin (wie Tampermonkey) in Ihrem Browser installieren. Dann können Sie Userscripts im Verwaltungsbereich des Plugins installieren und verwalten.
:::

::: details 💡 F: Kann ich Userscripts auf mobilen Geräten verwenden?
A: Typischerweise unterstützt der Standardbrowser mobiler Geräte keine Userscripts. Einige spezielle Browser bieten jedoch Plugins oder Erweiterungen mit entsprechenden Funktionen an.
:::

::: details 💡 F: Wie deaktiviere oder lösche ich Userscripts?
A: Sie können spezifische Greasemonkey-Skripte im Verwaltungsbereich des Userscript-Plugins deaktivieren oder löschen. Sie können auch das gesamte Skript-Manager-Plugin vorübergehend deaktivieren, um alle Skripte auszuschalten.
:::