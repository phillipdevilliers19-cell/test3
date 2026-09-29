# AVA Internal V46

Stable architecture cleanup and theme/data regression fix.

## Key changes
- Single core theme controller and single navigation controller.
- Light theme is the default; dark theme is controlled by `body.dark-theme`.
- Removed duplicate topbar/theme/navigation fallback handlers.
- Cache-busted CSS and JS to V46.
- OEM export/import schemas are compatible with the full backup importer.
- Backup import validates data shape and preserves a valid active Super Admin.
- Existing application, OEM, Scraper, Visualiser, Admin, permissions and portfolio functionality retained.

## Deployment
Replace the complete contents of the GitHub Pages app with this version. Do not mix V46 files with older versions.


V54 fixes the GitHub Pages Home Screen launch path and stabilizes the top-right header controls.
