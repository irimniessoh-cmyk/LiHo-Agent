# Liho — changes prepared for GitHub

## Latest update
- Removed the “داده نمونه” action from Settings.
- Updated JSON backup labels and instructions for the iPhone Safari flow.
- Backup exports use the browser save picker when available and attempt the iOS file-sharing flow so the user can choose “Save to Files”. iOS Safari does not provide a direct web save-location picker; it requires the share-sheet route.
- Kept encrypted JSON backup and restore support.
- Updated the service-worker cache version to v24 so deployed clients can refresh the app shell.

## Earlier accumulated app changes
- Added editing for category names and emoji in the transaction category picker and category-management screen, including overrides for built-in categories.
- Fixed Jalali month lengths and installment date progression, including clamping installment dates in shorter months.
- Added swipe-left payment for due installments, removed the detail-page payment button, and refined the tear animation.
- Changed transaction and monthly-obligation detail separators from dots to dashes.

## Validation
- JavaScript syntax checks passed for `index.html`, `preview.html`, and `sw.js`.
- Duplicate HTML IDs check passed.
- ZIP archive integrity test passed.

## Publishing status
These files are prepared for upload. No GitHub commit or push has been made from this workspace.
