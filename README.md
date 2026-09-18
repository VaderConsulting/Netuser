# Netuser

Regional Transportation Council VB6 NetAPI viewer (project Project1, form `FUserInfo` caption "NetUserInfo1 Test"). Class `CNetUser` wraps `NetUserGetInfo` levels 0-3 plus `NetUserGetGroups` / `NetUserGetLocalGroups`, and the form prints privilege, home directory, logon hours, last logon/off, account expiry, and group membership for a chosen server and username. Defaults to the current NT machine and user on load.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `Project1` (`Netuser.vbp`) | VB6 | WinForms exe | NetUserGetInfo level 0-3 viewer with group lists |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `Netuser.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Windows NT/2000+ with NetAPI32 access to query user accounts

## Attribution and provenance

Working copy from Dave Robinson's OneDrive Historical Dev folder `VB/Old/Netuser`.
Company names in project files: Regional Transportation Council.
Third-party attribution: Regional Transportation Council. See `THIRD_PARTY_NOTICES.md`.

## License

Third-party code remains under its original terms (or none, where none were supplied). See `THIRD_PARTY_NOTICES.md`. Do not treat this tree as VaderConsulting original MIT-licensed work.
