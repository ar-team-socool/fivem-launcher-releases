# AR Launcher — Releases

Official **download & auto-update channel** for **AR Launcher** — AR Team's companion launcher for
connecting to their FiveM server.
ช่องทางดาวน์โหลด + อัปเดตอัตโนมัติ (อย่างเป็นทางการของ AR Team) สำหรับ AR Launcher — ตัวช่วยเชื่อมต่อเข้าเซิร์ฟเวอร์ FiveM ของ AR Team

> **Not affiliated with Cfx.re or the official FiveM client.** This is an independent, third-party
> launcher made by AR Team for their own server.
> _ไม่เกี่ยวข้องกับ Cfx.re หรือ FiveM อย่างเป็นทางการ — เป็น launcher อิสระของ AR Team สำหรับเซิร์ฟเวอร์ของตนเอง_

## What is this repo?

AR Launcher's **release channel** — not its source. Every release attaches:

- the Windows **installer** — `*-setup.exe` (NSIS), and
- the auto-update manifests — `latest.yml` + `*.blockmap` (consumed by electron-updater in-app).

Builds are published **automatically by CI** from the main, private repository. **No source code
lives here** — please don't push source to this repo.

## Install

1. Download the latest **`*-setup.exe`** from the **[Releases](../../releases)** page.
2. Run it — it installs **per-user**, so **no administrator rights are required**.
3. Open AR Launcher; from then on it **keeps itself up to date** from this channel.

### Requirements

- **Windows 10 / 11** (64-bit) — Windows-only (FiveM and GTA V are Windows-only).
- **Steam** installed, signed in, and **running**.
- **GTA V** and **FiveM** installed.

> Tip: run AR Launcher and FiveM at the **same privilege level** (both as a normal user) so the
> launcher can pair with the game correctly.

## License

Proprietary — © AR Team. All rights reserved. The binaries distributed here are **not** open source.
