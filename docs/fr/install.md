---
sidebarDepth: 3
next: usage
head:
  - - meta
    - name: description
      content: Comment ajouter le défilement infini à un site web ? Meilleurs scripts Greasemonkey pour la productivité
  - - meta
    - name: keywords
      content: pagination automatique, défilement infini, automatisation du chargement de page, récupération de contenu, chargement automatique de page
---
# Guide d'installation
## Gestionnaire de scripts
Pagetual est basé sur Greasemonkey, il nécessite donc un gestionnaire de scripts pour fonctionner.

### 🛠️ Exemples de gestionnaires de scripts

<table>
  <tbody>
    <td>
      <details>
        <summary style="cursor:pointer;">🖥️ Ordinateur de bureau</summary>
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
        <summary style="cursor:pointer;">📱 Mobile (Android)</summary>
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
        <summary style="cursor:pointer;">🍎 Mobile (iOS)</summary>
        <ul>
          <li>Safari: <a href="http://tampermonkey.net/?browser=safari">Tampermonkey</a> | <a href="https://apps.apple.com/app/userscripts/id1463298887">Userscripts</a></li>
          <li><a href="https://gear4.app/">Gear</a></li>
        </ul>
      </details>
    </td>
  </tbody>
</table>

## Installer Pagetual
<div style="display: flex"><a style="transition: box-shadow .2s; display: inline-block; background-color: #e2510a; padding: 0.7rem 1.1rem; color: #fff; text-decoration: none; font-weight: 700; height: fit-content; margin: 6px 0 0 10px;" href="https://tomkabel.github.io/UserScripts/Pagetual/pagetual.user.js">Github</a></div>

::: details 💡 Q: Qu'est-ce qu'un "script Greasemonkey de navigateur"?
R: "Greasemonkey" est un plug-in qui exécute et gère des scripts sur le navigateur. Un script est un morceau de code qui optimise votre expérience de navigation web. Une fois installés, certains scripts ajoutent de nouvelles fonctionnalités au site, certains rendent l'interface du site plus facile à utiliser, et certains cachent les publicités gênantes sur le site.
:::

::: details 💡 Q: Pourquoi Pagetual est-il écrit comme un userscript plutôt qu'une extension?
R: Parce que Pagetual possède de puissantes capacités d'exécution de code personnalisé pour implémenter des règles de pagination, et les extensions ont des restrictions sur les capacités d'exécution de code personnalisé pour des raisons de sécurité. En outre, les userscripts sont plus flexibles et peuvent fonctionner sur presque tous les systèmes d'exploitation, tels que Windows/MAC/iOS/Android.
:::

::: details 💡 Q: Les scripts utilisateur sont-ils sûrs?
R: Les userscripts eux-mêmes ne sont pas malveillants, mais la sécurité dépend des scripts que vous choisissez d'installer. Il est recommandé de n'obtenir des scripts qu'à partir de sources fiables et de lire attentivement le code du script. Et bien sûr, vous pouvez me faire confiance - je contribue à la communauté open-source depuis dix ans.
:::

::: details 💡 Q: Comment installer un script utilisateur?
R: Tout d'abord, vous devez installer un plug-in de gestionnaire de scripts (tel que Tampermonkey) sur votre navigateur. Vous pouvez ensuite installer et gérer les userscripts dans l'interface de gestion du plug-in.
:::

::: details 💡 Q: Puis-je utiliser des userscripts sur des appareils mobiles?
R: Généralement, le navigateur par default des appareils mobiles ne prend pas en charge les scripts utilisateur. Cependant, certains navigateurs spécifiques proposent des plug-ins ou des extensions avec des fonctions connexes.
:::

::: details 💡 Q: Comment désactiver ou supprimer des userscripts?
R: Vous pouvez désactiver ou supprimer des scripts Grease Monkey spécifiques dans l'interface de gestion du plug-in de script utilisateur. Vous pouvez également désactiver temporairement l'ensemble du plug-in du gestionnaire de scripts pour empêcher tous les scripts de s'exécuter.
:::