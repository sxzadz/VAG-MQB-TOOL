# VAG MQB TOOL

[中文](#中文) · [Русский](#русский) · [English](#english)

---

## 中文

面向 VAG MQB 平台 J533 网关的桌面 GUI 与命令行工具：部件保护（CP / IKA / FSC /
SWaP）、工程模式、ZDC 参数化、Flash / DataFlash 检查，以及通过 VAS 6154、J2534、
gs_usb / slcan、SocketCAN 或 PCAN 的 CAN 读写。

当前版本 **2.2.3**。界面语言：**简体中文（默认）**、**俄语**、**英语**。GUI 与 CLI 默认中文，
可用 `--lang ru` / `--lang en` 或 `CONTI_CP_LANG` 切换。发布仓库：
<https://github.com/sxzadz/VAG-MQB-TOOL>。

### 版本记录

当前发布版本 **2.2.3**（tag `v2.2.3`）。更新检查默认开启，帮助菜单提供“检查更新”入口；
打包版启动时会静默查询最新发布，源码直接运行只在手动点击时联网。

### 使用与分发

本项目由 SN.SXZADZ 维护，发布包携带 `README.md`。

允许使用本软件进行付费维修/诊断。**使用风险自负**：写入前务必备份已验证的完整网关数据，
不要在一辆不能没有它的车上操作。

---

## Русский

Настольное GUI-приложение и инструмент командной строки для шлюза VAG MQB J533: защита
компонентов (CP / IKA / FSC / SWaP), инженерный режим, параметризация ZDC, проверка Flash /
DataFlash, а также чтение и запись CAN через VAS 6154, J2534, gs_usb / slcan, SocketCAN или PCAN.

Текущая версия — **2.2.3**. Языки интерфейса: **китайский (упрощённый, по умолчанию)**,
**русский**, **английский**. GUI и CLI по умолчанию используют китайский; переключение —
`--lang ru` / `--lang en` или `CONTI_CP_LANG`. Репозиторий выпусков:
<https://github.com/sxzadz/VAG-MQB-TOOL>.

### История версий

Текущий выпуск — **2.2.3** (тег `v2.2.3`). Проверка обновлений включена по умолчанию, пункт
«Проверить обновления» есть в меню «Справка»; собранная версия проверяет последний выпуск при
запуске без запросов к пользователю, запуск из исходников обращается к сети только по нажатию
пункта меню.

### Использование и распространение

Проект сопровождается SN.SXZADZ. В каждый архив входит `README.md`.

Платное использование программы для ремонта и диагностики разрешено. **Используйте на свой
риск**: перед записью обязательно сохраните проверенную полную копию данных шлюза; не работайте
на автомобиле, без которого нельзя остаться.

---

## English

Desktop GUI and command-line tool for the VAG MQB J533 gateway: component protection
(CP / IKA / FSC / SWaP), engineering mode, ZDC parameterisation, Flash / DataFlash checks, and
CAN read/write over VAS 6154, J2534, gs_usb / slcan, SocketCAN or PCAN.

Current version **2.2.3**. UI languages: **Simplified Chinese (default)**, **Russian**,
**English**. The GUI and CLI default to Chinese; switch with `--lang ru` / `--lang en` or
`CONTI_CP_LANG`. Release repository: <https://github.com/sxzadz/VAG-MQB-TOOL>.

### Version history

The current release is **2.2.3** (tag `v2.2.3`). Update checks are on by default, with a "Check
for updates" item in the Help menu; the packaged build checks the latest release silently at
startup, while a source run only touches the network when that menu item is clicked.

### Usage and distribution

This project is maintained by SN.SXZADZ. Every archive ships `README.md`.

Paid repair and diagnostics with this software are allowed. **Use at your own risk**: always back
up a verified full copy of the gateway data before writing, and never work on a car you cannot do
without.

---
