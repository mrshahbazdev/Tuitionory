# Tuitionory — Microsoft Store listing

## Short description (≤ 100 words? field: what your app does)
Offline school office: students, fees, 3-part bank challans, exams, attendance, payroll — no account, no internet.

## Description
Tuitionory is a complete, offline-first school office for small private schools — everything from admission to fee collection to report cards runs on one Windows PC, encrypted, with no subscription and no internet connection.

Students & classes:
- Admission form with photo, guardian contact and sibling linking; bulk Excel/CSV import with per-row error preview
- Classes, sections, roll numbers and registers per academic session
- Attendance (P/A/L) with monthly percentage report and printable register

Fees & challans:
- Fee heads, per-class plans, per-student overrides and approvable concessions (sibling/staff/merit)
- Monthly challan generation for a class or the whole school — three-part print (bank / school / parent copy) with arrears carried forward and letterhead offset
- Collection register with cash/bank/online modes, receipts, and reversals (receipts are never deleted — only reversed with a reason)
- Class-wise defaulter list with one-click WhatsApp reminders

Exams & staff:
- Subjects, exams, marks entry and printable report cards with grades
- Staff records, leaves, attendance and monthly payslips (absent-day auto-deduction)

Also included: transport routes with fee assignment, weekly timetable, a small library register, user roles (Principal / Accountant / Class teacher / Clerk with PINs), daily auto-backup, and an optional second-PC LAN mode protected by an access code.

Privacy first: all records — including children's data — stay encrypted on the school's own computer. The app makes no internet requests; the school is the data controller. On first launch a fully populated fictional sample school lets you try everything safely.

## Search terms
school management, fee challan, fee collection, school fees, attendance, report card, marks, offline school software, students register, payslip

## What's new
First release.

## Support contact
mrshahbaznns@gmail.com

## Category / subcategory
Education > Instructional tools (Business also acceptable)

## Age rating
Everyone (no age gate). Note for tester: the app manages children's school records — parents' consent is the school's responsibility; data never leaves the device.

## Testing notes for evaluators
Launch the app → accept the consent screen → a fictional sample school ("Al-Noor Model School", 30 students, 2 classes, a fee plan and this month's challans) loads automatically. Suggested path:
1. Students — browse the 30-student register.
2. Challans — preview this month's challans, press Print on any row to see the 3-part (bank/school/parent) A4 layout.
3. Collection — pick an unpaid challan, record a partial payment, print the receipt.
4. Defaulters — view the list; WhatsApp button opens a wa.me link (no internet needed to see the message text).
5. Exams — view First Term marks and print all report cards.
6. Attendance — mark today's register; Staff → Payroll — issue a payslip.
7. Settings — create a user with a role, switch LAN sharing on/off (off by default; requires an access code).

Declared capability privateNetworkClientServer: used only for the optional, user-initiated LAN host mode so a second office PC can open the same data in a browser with an access code. It never connects to the internet. runFullTrust is required for the encrypted local database (SQLCipher) and for printing documents.

## Privacy policy
The app stores all data locally, encrypted (SQLCipher + OS credential store), makes no internet requests, and collects no analytics. The school is the data controller for children's records.
