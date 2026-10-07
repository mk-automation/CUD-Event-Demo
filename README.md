# CUD CHEDS Event Management — Full GitHub Demo v14

Static interactive demo prepared for GitHub Pages.

## Included
- Event Organizer home
- Updated organization Pre-Event form
- Automatic Event ID
- Attendance QR generation and PDF download
- QR opens `attendance.html` directly
- Participant attendance form
- Manual attendance and post-event evidence
- Post-event locking
- IRP login/dashboard and Excel export
- IRP school target settings
- Executive Dashboard with target achievement

## IRP demo login
- Username: `irp@cud.ac.ae`
- Password: `IRP123!`

## Publish on GitHub Pages
1. Create a new GitHub repository.
2. Upload **all files in this folder to the repository root**.
3. Commit the files.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select `main` and `/ (root)`, then Save.
7. Open the GitHub Pages URL after deployment.

## Important static-demo limitation
GitHub Pages has no shared MySQL/PHP backend. Event and target data are stored in each browser's `localStorage`.
A QR scanned on another phone opens the correct attendance sheet, but that phone's attendance submission cannot update the organizer's browser count centrally. The final PHP/MySQL server version will do that.

Do not use this static demo as the production attendance system.


## Real source data
Preloaded with all 60 records from the uploaded Pre QR workbook. Imported records begin as Pre-Event Submitted with attendance 0 because the source is pre-event data.


## Post-event integration
Imported 30 post-event submissions. 28 unique events are now marked **Post-Event Submitted & Locked**; 32 remain **Pre-Event Submitted**. Evidence URLs are retained. Attendance bands are preserved exactly rather than converted to fabricated counts.
