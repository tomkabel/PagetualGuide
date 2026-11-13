---
sidebarDepth: 3
next: usage
head:
  - - meta
    - name: description
      content: Cách thêm cuộn vô hạn vào một trang web? Các Greasemonkey scripts tốt nhất để tăng năng suất
  - - meta
    - name: keywords
      content: tự động phân trang, cuộn vô hạn, tự động tải trang, tìm nạp nội dung, tự động tải trang
---
# Cài đặt trong 5 giây

<img src="https://s2.loli.net/2024/09/11/qeM1ZQjRXvaJnSf.gif" alt="pagetual install" width=740 height=524 />

## 1. Cài đặt trình quản lý script - 3 giây
Pagetual dựa trên Greasemonkey, vì vậy nó yêu cầu một trình quản lý script để chạy👇.

### 🛠️ Ví dụ về các trình quản lý script

Hãy đảm bảo bạn đã bật "Allow User Scripts" cho phiên bản MV3 của tiện ích mở rộng.

<table>
  <tbody>
    <td>
      <details open>
        <summary style="cursor:pointer;">🖥️ Máy tính để bàn</summary>
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
        <summary style="cursor:pointer;">📱 Thiết bị di động (Android)</summary>
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
        <summary style="cursor:pointer;">🍎 Thiết bị di động (iOS)</summary>
        <ul>
          <li>Safari: <a href="http://tampermonkey.net/?browser=safari">Tampermonkey</a> | <a href="https://apps.apple.com/app/userscripts/id1463298887">Userscripts</a></li>
          <li><a href="https://gear4.app/">Gear</a></li>
        </ul>
      </details>
    </td>
  </tbody>
</table>


## 2. Cài đặt Pagetual - 2 giây
<div style="display: flex"><a style="transition: box-shadow .2s; display: inline-block; background-color: #e2510a; padding: 0.7rem 1.1rem; color: #fff; text-decoration: none; font-weight: 700; height: fit-content; margin: 6px 0 0 10px;" href="https://tomkabel.github.io/UserScripts/Pagetual/pagetual.user.js">Github</a></div>

::: details 💡 H: "Browser Greasemonkey script" là gì?
Đ: "Greasemonkey" là một plugin chạy và quản lý các script trên trình duyệt. Một script là một đoạn mã giúp tối ưu hóa trải nghiệm duyệt web của bạn. Sau khi được cài đặt, một số script sẽ thêm các chức năng mới vào trang web, một số giúp giao diện trang web dễ sử dụng hơn, và một số khác ẩn các quảng cáo phiền toái trên trang.
:::

::: details 💡 H: Tại sao Pagetual lại được viết dưới dạng một userscript thay vì một tiện ích mở rộng?
Đ: Vì Pagetual có khả năng thực thi mã tùy chỉnh mạnh mẽ để triển khai các quy tắc phân trang, trong khi các tiện ích mở rộng có những hạn chế về khả năng thực thi mã tùy chỉnh vì lý do bảo mật. Ngoài ra, userscripts linh hoạt hơn và có thể chạy trên hầu hết mọi hệ điều hành, chẳng hạn như Windows/MAC/iOS/Android.
:::

::: details 💡 H: Userscript có an toàn không?
Đ: Bản thân userscripts không độc hại, nhưng mức độ an toàn phụ thuộc vào các script mà bạn chọn cài đặt. Nên chỉ lấy script từ các nguồn đáng tin cậy và đọc kỹ mã script. Và tất nhiên, bạn có thể tin tưởng tôi - tôi đã đóng góp cho cộng đồng mã nguồn mở trong mười năm.
:::

::: details 💡 H: Làm thế nào để cài đặt userscript?
Đ: Trước tiên, bạn cần cài đặt một plugin quản lý script (như Tampermonkey) trên trình duyệt của mình. Sau đó, bạn có thể cài đặt và quản lý các userscript trong giao diện quản lý plugin.
:::

::: details 💡 H: Tôi có thể sử dụng userscript trên thiết bị di động không?
Đ: Thông thường, trình duyệt mặc định của các thiết bị di động không hỗ trợ userscript. Tuy nhiên, một số trình duyệt cụ thể có cung cấp các plugin hoặc tiện ích mở rộng có chức năng liên quan.
:::

::: details 💡 H: Làm thế nào để vô hiệu hóa hoặc xóa userscript?
Đ: Bạn có thể vô hiệu hóa hoặc xóa các Grease Monkey scripts cụ thể trong giao diện quản lý plugin userscript. Bạn cũng có thể tạm thời vô hiệu hóa toàn bộ plugin Script Manager để ngừng tất cả các script đang chạy.
:::