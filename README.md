# ShiftLedger — independent timesheet calculator

Static HTML app; Vercel Framework Preset: Other, Root Directory: ./, no build command.

**Storage:** All sheets and saved period snapshots stay in this browser's localStorage. No backend, account, analytics or cloud database. The backup JSON and printed PDFs may contain personal information, so only save or share them in approved locations.

**Snapshots:** Every Save adds another dated copy, even for the same pay period. Editing a reopened copy does not change an earlier snapshot until a new Save. Backups are manually exported and not tamper-proof or a formal audit trail.

**Feedback:** Copies a feedback message or opens a user-addressed email draft. No message is sent automatically; no recipient is configured. Avoid personal information in feedback.

**Logo:** Generated ShiftLedger brand icon; app header branding is excluded from the paper print layout. Not an official OCDE product.

Deploy by replacing existing GitHub repository root files with this package's files; Vercel should rebuild automatically.
