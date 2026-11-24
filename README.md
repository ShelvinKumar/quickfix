# QuickFix

IT self-service fixer for Windows 10/11 and macOS.

This repository hosts QuickFix **update releases**. QuickFix on each USB checks the latest release here when it starts on a computer with internet, verifies the SHA-256 fingerprint in `manifest.json`, and installs the new version.

Each release contains: `manifest.json`, `QuickFix.ps1` (Windows) and `QuickFix-mac.command` (macOS).
