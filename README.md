# FiveM Launcher — Releases

Official **download & auto-update channel** for the FiveM Launcher desktop app.
ช่องทางดาวน์โหลด + อัปเดตอัตโนมัติ (อย่างเป็นทางการ) ของ FiveM Launcher

> ## ⚠️ Work in progress — no public build yet
>
> The launcher is still in active development. **No installer has been published here yet** and
> auto-update is not live — this channel opens once the first version ships. Not for production use.
>
> **ภาษาไทย:** โปรเจกต์ยังพัฒนาอยู่ — **ยังไม่มีไฟล์ติดตั้งให้ดาวน์โหลด** และระบบอัปเดตอัตโนมัติยังไม่เปิด
> ช่องทางนี้จะเริ่มใช้งานเมื่อปล่อยเวอร์ชันแรก ยังไม่ควรนำไปใช้งานจริง

## What is this repo?

The FiveM Launcher's **release channel** — not its source. Every release attaches:

- the Windows **installer** — `*-setup.exe` (NSIS), and
- the auto-update manifests — `latest.yml` + `*.blockmap` (consumed by electron-updater in-app).

Builds are published **automatically by CI** from the main, private repository. **No source code
lives here** — please don't push source to this repo.

## Install (once a build is available)

1. Download the latest **`*-setup.exe`** from the **[Releases](../../releases)** page.
2. Run it — it installs **per-user**, so **no administrator rights are required**.
3. Open the launcher; from then on it **keeps itself up to date** from this channel.

### Requirements

- **Windows 10 / 11** (64-bit) — Windows-only (FiveM and GTA V are Windows-only).
- **Steam** installed, signed in, and **running**.
- **GTA V** and **FiveM** installed.

> Tip: run the launcher and FiveM at the **same privilege level** (both as a normal user) so the
> launcher can pair with the game correctly.

## License

Proprietary — © AR Team. All rights reserved. The binaries distributed here are **not** open source.
