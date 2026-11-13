---
sidebarDepth: 3
next: usage
head:
  - - meta
    - name: description
      content: Como adicionar rolagem infinita a um site? Melhores scripts Greasemonkey para produtividade
  - - meta
    - name: keywords
      content: auto pager, rolagem infinita, automação de carregamento de página, busca de conteúdo, carregamento automático de página
---
# Instalar em 5 segundos

<img src="https://s2.loli.net/2024/09/11/qeM1ZQjRXvaJnSf.gif" alt="instalação do pagetual" width=740 height=524 />

## 1. Instalar gerenciador de scripts - 3 segundos
Pagetual é baseado em Greasemonkey, então ele requer um gerenciador de scripts para rodar👇.

### 🛠️ Exemplo de gerenciadores de scripts

Certifique-se de habilitar "Permitir Scripts de Usuário" para a versão MV3 da extensão.

<table>
  <tbody>
    <td>
      <details open>
        <summary style="cursor:pointer;">🖥️ Área de Trabalho</summary>
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
        <summary style="cursor:pointer;">📱 Celular (Android)</summary>
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
        <summary style="cursor:pointer;">🍎 Celular (iOS)</summary>
        <ul>
          <li>Safari: <a href="http://tampermonkey.net/?browser=safari">Tampermonkey</a> | <a href="https://apps.apple.com/app/userscripts/id1463298887">Userscripts</a></li>
          <li><a href="https://gear4.app/">Gear</a></li>
        </ul>
      </details>
    </td>
  </tbody>
</table>

## 2. Instalar Pagetual - 2 segundos
<div style="display: flex"><a style="transition: box-shadow .2s; display: inline-block; background-color: #e2510a; padding: 0.7rem 1.1rem; color: #fff; text-decoration: none; font-weight: 700; height: fit-content; margin: 6px 0 0 10px;" href="https://tomkabel.github.io/UserScripts/Pagetual/pagetual.user.js">Github</a></div>

::: details 💡 P: O que é "script Greasemonkey de navegador"?
R: "Greasemonkey" é um plug-in que executa e gerencia scripts no navegador. Um script é um pedaço de código que otimiza sua experiência de navegação na web. Uma vez instalados, alguns scripts adicionam novas funcionalidades ao site, alguns tornam a interface do site mais fácil de usar e alguns ocultam anúncios irritantes no site.
:::

::: details 💡 P: Por que o Pagetual é escrito como um userscript em vez de uma extensão?
R: Porque o Pagetual possui poderosas capacidades de execução de código personalizado para implementar regras de paginação, e as extensões têm restrições nas capacidades de execução de código personalizado por razões de segurança. Além disso, os userscripts são mais flexíveis e podem ser executados em quase qualquer sistema operacional, como Windows/MAC/iOS/Android.
:::

::: details 💡 P: Os userscripts são seguros?
R: Os userscripts em si não são maliciosos, mas a segurança depende dos scripts que você escolhe instalar. Recomenda-se obter scripts apenas de fontes confiáveis e ler o código do script cuidadosamente. E, claro, você pode confiar em mim - eu tenho contribuído para a comunidade de código aberto por dez anos.
:::

::: details 💡 P: Como instalar um userscript?
R: Primeiro, você precisa instalar um plug-in gerenciador de scripts (como o Tampermonkey) em seu navegador. Você pode então instalar e gerenciar userscripts na interface de gerenciamento do plug-in.
:::

::: details 💡 P: Posso usar userscripts em dispositivos móveis?
R: Normalmente, o navegador padrão de dispositivos móveis não suporta userscripts. No entanto, alguns navegadores específicos fornecem plug-ins ou extensões com funções relacionadas.
:::

::: details 💡 P: Como desabilitar ou excluir userscripts?
R: Você pode desabilitar ou excluir scripts específicos do Grease Monkey na interface de gerenciamento do plug-in de userscript. Você também pode desabilitar temporariamente todo o plug-in do Gerenciador de Scripts para interromper a execução de todos os scripts.
:::
