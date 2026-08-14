# Privacy Policy — 說事 SpeakTask

_Last updated: 2026-08-15_

English | 繁體中文在下方 ↓

SpeakTask is an offline to-do list that can mirror your calendars onto the same
timeline. The short version: **nothing leaves your phone.**

## What data the app handles

- **The tasks you create.** Title, due time, repeat rule, an optional note, and
  whether the task is done. Stored in a private database on your device.
- **The text of what you said**, when you add a task by voice, kept so you can
  check what was heard.
- **Events from the calendars you tick.** Title, time, and the identifiers
  needed to keep the copy in step with the original.

## What the app does NOT do

- **No internet.** The app declares **no `INTERNET` permission**. It is
  technically incapable of sending your data anywhere.
- **No servers, no cloud, no accounts, no sync.**
- **No analytics, no advertising, no tracking, no third-party SDKs.**
- **No selling or sharing** of any data with anyone.
- **It never writes to your calendars.** The app requests read access only
  (`READ_CALENDAR`); it holds no permission that would let it add, change or
  delete an event, so this is enforced by Android rather than by our promise.

## Speech recognition

Voice entry uses Android's built-in speech recogniser. The audio is handled by
your device's system speech service (typically Google's, depending on your
phone), under that service's own privacy policy — not by this app. SpeakTask
receives only the resulting text and never stores or transmits the audio itself.

## Permissions used

- **Microphone (`RECORD_AUDIO`)** — only while you are recording a task by
  voice. No background listening; the app has no service that could do so.
- **Calendar, read only (`READ_CALENDAR`)** — used only to mirror the calendars
  you tick in settings onto the timeline. Nothing is written back. Untick a
  calendar and its mirrored copies stop being updated.
- **Notifications (`POST_NOTIFICATIONS`)** — to show the reminder itself.
- **Exact alarms (`USE_EXACT_ALARM` / `SCHEDULE_EXACT_ALARM`)** — a reminder
  that fires "sometime around" its time is not a reminder, so the app schedules
  exact alarms.
- **Run at startup (`RECEIVE_BOOT_COMPLETED`)** — Android clears all scheduled
  alarms when the phone restarts; this lets the app put your pending reminders
  back. Nothing else runs at boot.

## Where data is stored & how long

In SpeakTask's private database on your device. It stays until you delete the
tasks or uninstall the app, which removes everything. Mirrored calendar events
are copies: deleting them here never touches your real calendar.

## Children

The app is not directed at children and collects no personal data online.

## Changes

Any future change to this policy will be published at this URL with an updated
date.

## Contact

Questions: open an issue at
<https://github.com/chengyuchen-sideproject/privacy-policies/issues>.

---

# 隱私權政策 — 說事 SpeakTask

_最後更新：2026-08-15_

說事是一款**離線的語音待辦 App**，可以把你的行事曆鏡像到同一條時間軸。
一句話：**所有資料都不離開你的手機。**

## App 會處理的資料

- **你建立的待辦**：標題、時間、重複規則、選填備註、完成狀態。
  存在裝置內的私有資料庫。
- **語音建立時你說的那句話的文字**，保留下來讓你可以核對聽到的內容。
- **你勾選的行事曆裡的事件**：標題、時間，以及用來跟原始事件保持同步的識別碼。

## App 不會做的事

- **無網路**：App **未宣告 `INTERNET` 權限**，技術上根本無法把資料傳到任何地方。
- **無伺服器、無雲端、無帳號、無同步。**
- **無分析、無廣告、無追蹤、無第三方 SDK。**
- **不販售、不分享**任何資料給任何人。
- **永遠不會寫回你的行事曆**：App 只申請**唯讀**權限（`READ_CALENDAR`），
  它根本沒有能新增、修改或刪除事件的權限——這是**由 Android 系統層保證**的，
  不只是我們的承諾。

## 語音辨識

語音建立待辦使用 Android 內建的語音辨識。**音訊是交由你手機的系統語音服務處理**
（通常是 Google 的，視手機而定），適用該服務自己的隱私權政策，不是本 App 的。
說事只拿到辨識後的文字，不會儲存或傳送音訊本身。

## 使用的權限

- **麥克風（`RECORD_AUDIO`）**：只在你按下語音建立、實際錄音的那段期間使用。
  不會背景監聽——這個 App 沒有任何可以背景錄音的服務。
- **行事曆，唯讀（`READ_CALENDAR`）**：只用於把你在設定頁勾選的行事曆鏡像到時間軸。
  不會寫回任何東西。取消勾選後，該行事曆的鏡像副本就停止更新。
- **通知（`POST_NOTIFICATIONS`）**：用於顯示提醒本身。
- **精確鬧鐘（`USE_EXACT_ALARM` / `SCHEDULE_EXACT_ALARM`）**：
  「大約那個時間」響的提醒不算提醒，所以使用精確鬧鐘。
- **開機啟動（`RECEIVE_BOOT_COMPLETED`）**：手機重開機時 Android 會清掉所有已排定的鬧鐘，
  這個權限讓 App 把你還沒到期的提醒重新排回去。開機時不做其他任何事。

## 資料儲存位置與保留時間

存在說事於裝置內的私有資料庫。會保留到你自己刪除或解除安裝 App（會刪除全部）為止。
鏡像進來的行事曆事件是**副本**，在這裡刪除它們絕不會動到你真正的行事曆。

## 兒童

本 App 非針對兒童設計，且不在線上收集任何個人資料。

## 變更

日後政策若有變更，會在此網址更新並附上新日期。

## 聯絡

有問題請至 <https://github.com/chengyuchen-sideproject/privacy-policies/issues> 開 issue。
