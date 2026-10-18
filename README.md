# Gradeache desktop app

Current release: **2.0.0** (Windows x64 portable executable).

## For students

Send users only `Gradeache-v2.0.0.exe` from `dist/`. They can double-click it to open the app. No installation or separate runtime is needed. Course data stays on that Windows account and device; it does not move automatically to another computer.

## For development

The Windows x64 portable executable is built with Electron and electron-builder. To rebuild it from source, a developer needs Node.js, then runs `npm install` and `npm run build:win`. The executable is named for the package version, for example `dist/Gradeache-v2.0.0.exe` for this release.
