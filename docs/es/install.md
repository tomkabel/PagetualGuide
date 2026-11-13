---
sidebarDepth: 3
next: usage
head:
  - - meta
    - name: description
      content: ¿Cómo añadir scroll infinito a un sitio web? Los mejores scripts de Greasemonkey para la productividad
  - - meta
    - name: keywords
      content: paginador automático, scroll infinito, automatización de carga de página, obtención de contenido, carga automática de página
---
# Guía de instalación
## Gestor de scripts
Pagetual se basa en Greasemonkey, por lo que requiere un gestor de scripts para ejecutarse.

### 🛠️ Ejemplos de gestores de scripts

<table>
  <tbody>
    <td>
      <details>
        <summary style="cursor:pointer;">🖥️ Escritorio</summary>
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
        <summary style="cursor:pointer;">📱 Móvil (Android)</summary>
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
        <summary style="cursor:pointer;">🍎 Móvil (iOS)</summary>
        <ul>
          <li>Safari: <a href="http://tampermonkey.net/?browser=safari">Tampermonkey</a> | <a href="https://apps.apple.com/app/userscripts/id1463298887">Userscripts</a></li>
          <li><a href="https://gear4.app/">Gear</a></li>
        </ul>
      </details>
    </td>
  </tbody>
</table>

## Instalar Pagetual
<div style="display: flex"><a style="transition: box-shadow .2s; display: inline-block; background-color: #e2510a; padding: 0.7rem 1.1rem; color: #fff; text-decoration: none; font-weight: 700; height: fit-content; margin: 6px 0 0 10px;" href="https://tomkabel.github.io/UserScripts/Pagetual/pagetual.user.js">Github</a></div>

::: details 💡 P: ¿Qué es un "script Greasemonkey para navegador"?
R: "Greasemonkey" es un complemento que ejecuta y gestiona scripts en el navegador. Un script es un fragmento de código que optimiza tu experiencia de navegación web. Una vez instalados, algunos scripts añaden nueva funcionalidad al sitio, otros facilitan el uso de la interfaz del sitio y otros ocultan anuncios molestos en el sitio.
:::

::: details 💡 P: ¿Por qué Pagetual está escrito como un userscript en lugar de una extensión?
R: Porque Pagetual tiene potentes capacidades de ejecución de código personalizado para implementar reglas de paginación, y las extensiones tienen restricciones en las capacidades de ejecución de código personalizado por razones de seguridad. Además, los userscripts son más flexibles y pueden ejecutarse en casi cualquier sistema operativo, como Windows/MAC/iOS/Android.
:::

::: details 💡 P: ¿Son seguros los userscripts?
R: Los userscripts en sí mismos no son maliciosos, pero la seguridad depende de los scripts que elijas instalar. Se recomienda obtener scripts solo de fuentes confiables y leer el código del script cuidadosamente. Y, por supuesto, puedes confiar en mí: he estado contribuyendo a la comunidad de código abierto durante diez años.
:::

::: details 💡 P: ¿Cómo instalar un userscript?
R: Primero, necesitas instalar un complemento de administrador de scripts (como Tampermonkey) en tu navegador. Luego puedes instalar y administrar userscripts en la interfaz de administración del complemento.
:::

::: details 💡 P: ¿Puedo usar userscripts en dispositivos móviles?
R: Normalmente, el navegador predeterminado de los dispositivos móviles no es compatible con los userscripts. Sin embargo, algunos navegadores específicos ofrecen complementos o extensiones con funciones relacionadas.
:::

::: details 💡 P: ¿Cómo deshabilitar o eliminar userscripts?
R: Puedes deshabilitar o eliminar scripts específicos de Grease Monkey en la interfaz de administración del complemento de userscripts. También puedes deshabilitar temporalmente todo el complemento del Administrador de Scripts para detener la ejecución de todos los scripts.
:::