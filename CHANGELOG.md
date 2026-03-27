# Changelog

All notable changes to **WizefDPI-Turkey** are documented in this file.

## WizefDPI-Turkey v0.2.3rc3 (Latest)

- **Release date:** October 11, 2024
- **Tag:** `release-0.2.3rc3-turkey`
- **Based on:** 53 commits since the previous upstream release snapshot

### Changes

- Initial release for WizefDPI-Turkey.
- Added Superonline alternative method.
- Fixed Turkish character bug and added auto-start for alternative method service installation.
- Added alternative method 2 and more detailed batch file instructions. (Thanks to RockHanger)
- Fixed a naming issue.
- Fixed auto-start behavior for alternative method 2.
- Added auto-elevated permission request. (Thanks to kaya51 and scropoolISreal)
- Added service start after installation. (Reverted)
- Added user confirmation via `CHOICE`. (Reverted)
- Rolled back earlier version because elevation prompts caused issues for some users. (Thanks to Elecksy for debugging)
- Added alternative methods 3 and 4 with predefined DNS addresses:
  - `service_install_dnsredir_turkey_alternative3_superonline.cmd`
  - `service_install_dnsredir_turkey_alternative4_superonline.cmd`
- Installed services now start automatically even on first setup  
  (PC restart still required for alternative methods 1 and 2).
- Fixed a bug caused by the `>` symbol in command files creating unnecessary temporary files during elevation flow. (Thanks to Egezenn)
- Added missing one-time runnable command files for alternative methods 3 and 4. (Thanks to berkyildizkaya)
- Added alternative methods 5 and 6 (method 5 includes predefined DNS; method 6 does not).

### Assets

- `wizefdpi-0.2.3rc3-turkey.zip` (302 KB, February 3, 2025)
- Source code (`.zip`)
- Source code (`.tar.gz`)
