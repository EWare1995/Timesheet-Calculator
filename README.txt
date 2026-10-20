ShiftLedger Unified Pilot (Dashboard + Timesheets V13 + Mileage V3)

TEST LOCALLY
1. Unzip the folder.
2. Open index.html to view the dashboard.
3. Click Timesheets or Mileage & Expenses.
4. Check sample calculations, CSV/backups, and draft printing in each tool.

DEPLOY ONLY AFTER TESTING
Upload the CONTENTS of this folder to your GitHub/Vercel project root (not the folder itself). Recommended: test in a branch or Vercel preview deployment before changing production.

IMPORTANT LOCAL STORAGE
Browser storage is origin-specific. Data from older standalone local HTML files may not automatically appear in the new hosted paths; use the export/backup functions from older copies and import them where supported. If you use the SAME Vercel hostname as the original timesheet, its existing localStorage values should continue to be accessible to the timesheet tool (since localStorage is shared across paths on the same origin). Mileage saved under another origin or local file may require JSON backup and restore.

Other notes: The timesheet file's original logo is embedded in the HTML; other supplied brand images are bundled. Mileage route estimates require third-party mapping services. The calculators remain independent and no Supabase integration is present. Nothing is an official OCDE form.
