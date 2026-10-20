# Caramba Live

**Tiếng Việt** · [English](#english)

Caramba Live đọc thế bi carom 3 băng từ **camera** hoặc **cửa sổ livestream** (YouTube, OBS, VLC…) và gợi ý các đường bi, kèm độ khó, độ dày, ép phê và lực của từng kiểu đánh. Dành cho bình luận viên, cơ thủ có bàn tập và câu lạc bộ. App dựng trên Solver của [Caramba Billiards](https://caramba-notebook.pages.dev).

Repo này **chỉ chứa bản đã biên dịch** để tải về, không có mã nguồn.

## Tải về

Vào mục **[Releases](../../releases/latest)** và chọn một trong hai:

| File | Dùng khi |
|---|---|
| `Caramba.Live_<phiên bản>_x64-setup.exe` | Muốn cài vào máy như app bình thường (có shortcut ở Start Menu). |
| `CarambaLive-portable-<phiên bản>.zip` | Không muốn cài: giải nén ra bất kỳ đâu (Desktop, USB…) rồi chạy. |

**Yêu cầu:** Windows 10 hoặc 11, 64-bit. Cần Microsoft Edge WebView2 Runtime (Windows 10/11 thường có sẵn; nếu app báo thiếu, tải bản *Evergreen Bootstrapper* tại https://developer.microsoft.com/microsoft-edge/webview2/).

## Cài đặt

**Bộ cài (setup.exe):** bấm đúp. App chưa được ký số nên Windows có thể hiện *"Windows protected your PC"*: bấm **More info** (Thông tin thêm) → **Run anyway** (Vẫn chạy).

**Bản portable (.zip):**
1. TRƯỚC khi giải nén: chuột phải file `.zip` → **Properties** → tích **Unblock** (Bỏ chặn) → **OK**.
2. Giải nén cả thư mục, bấm đúp `caramba-live.exe`. Đừng chạy thẳng trong file `.zip`.

Nếu Windows 11 báo *"Smart App Control blocked…"* (không có nút chạy): máy đang bật Smart App Control. **Đừng tự tắt** (tắt rồi không bật lại được nếu không cài lại Windows) — liên hệ người gửi app cho bạn.

## Bản quyền dùng thử

Bản này có **license dựng sẵn, dùng được đến hết ngày 31/12/2026**. Mở app là vào thẳng, không cần kích hoạt; chip trên thanh trên cùng ghi *"Bản dùng thử đến 31/12/2026 · còn N ngày"*.

Muốn dùng tiếp sau ngày đó: bấm chip bản quyền trên thanh trên cùng → **📋 Copy tin nhắn gửi anh Thai** → mở Zalo, dán (Ctrl+V) và gửi anh Thai để được cấp license.

## Hình trắng khi đọc cửa sổ Edge/Chrome

Nếu cửa sổ Edge/Chrome đang phát livestream bị một app khác (nhất là app full screen) che lên mà Caramba Live chỉ thấy **hình trắng**: trình duyệt đang ngừng vẽ cửa sổ bị che. Sửa một lần cho cả máy bằng file `sua-trinh-duyet-bi-che.ps1` có trong bản portable: chuột phải → **Run with PowerShell** → bấm **Yes** ở hộp quyền admin → **tắt hẳn** Edge/Chrome (Task Manager → End task mọi `msedge.exe` / `chrome.exe`, hoặc khởi động lại máy) rồi mở lại. Xem thêm mục 7 của `README-portable.txt`.

---

<a id="english"></a>

# Caramba Live (English)

Caramba Live reads a three-cushion carom position from a **camera** or a **livestream window** (YouTube, OBS, VLC…) and suggests routes, with the difficulty, thickness, english and speed of each shot style. Built for commentators, players with a practice table and clubs, on top of the [Caramba Billiards](https://caramba-notebook.pages.dev) solver.

This repository **only holds compiled builds** for download — no source code.

## Download

Open **[Releases](../../releases/latest)** and pick one:

| File | Use it when |
|---|---|
| `Caramba.Live_<version>_x64-setup.exe` | You want a normal install (Start Menu shortcut). |
| `CarambaLive-portable-<version>.zip` | You don't want to install: extract anywhere (Desktop, USB stick…) and run. |

**Requirements:** Windows 10 or 11, 64-bit, with the Microsoft Edge WebView2 Runtime (usually preinstalled; if the app says it is missing, get the *Evergreen Bootstrapper* from https://developer.microsoft.com/microsoft-edge/webview2/).

## Install

**Installer (setup.exe):** double-click it. The app is not code-signed yet, so Windows may show *"Windows protected your PC"*: click **More info** → **Run anyway**.

**Portable (.zip):**
1. BEFORE extracting: right-click the `.zip` → **Properties** → tick **Unblock** → **OK**.
2. Extract the whole folder and double-click `caramba-live.exe`. Do not run it from inside the `.zip`.

If Windows 11 says *"Smart App Control blocked…"* (no run button), Smart App Control is on. **Do not turn it off yourself** (it cannot be turned back on without reinstalling Windows) — contact whoever sent you the app.

## Trial license

This build has a **built-in license valid through 31/12/2026**. The app opens straight away with no activation; the chip in the top bar reads *"Built-in license until 31/12/2026 · N days left"*.

To keep using it after that date: click the license chip in the top bar → **📋 Copy message for Thai** → paste it into a message to Thai (Zalo) to get a license.

## White picture when reading an Edge/Chrome window

If the Edge/Chrome window playing the livestream is covered by another app (especially a full-screen one) and Caramba Live only sees a **white picture**, the browser has stopped painting the covered window. Fix it once for the whole PC with `sua-trinh-duyet-bi-che.ps1` from the portable build: right-click → **Run with PowerShell** → click **Yes** on the admin prompt → **fully close** Edge/Chrome (Task Manager → End task on every `msedge.exe` / `chrome.exe`, or restart the PC) and reopen it. See item 7 of `README-portable.txt`.

---

© Caramba Billiards. All rights reserved. Free to download and use under the terms above; redistribution or modification of the app is not permitted.
