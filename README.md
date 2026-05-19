🖨️ Air Printer App — iOS Manual QA Project

App: Air Printer — AirPrint for iPhone & iPad
Platform: iOS (iPhone & iPad)
Tester: Tanvi Sonani
Testing Period: July 2024 – Ongoing


📋 Project Summary
Complete manual QA testing project for an iOS AirPrint printing application. This project covers end-to-end functional, regression, performance, security, localization, and accessibility testing across 20 modules and 150+ test cases.

📱 Devices Tested
DeviceOSiPhone SEiOSiPhone 12iOSiPhone 14 ProiOSiPhone 15 Pro MaxiOSiPad (9th Gen)iPadOS

🌐 Languages Tested
English · Hindi · French · Spanish · German · Arabic (RTL)

🧪 Testing Types Covered

✅ Manual Functional Testing
✅ Regression Testing
✅ Permission Testing
✅ Performance Testing
✅ Localization & RTL Testing
✅ Accessibility Testing (VoiceOver, Dynamic Type)
✅ Security & Privacy Testing
✅ Crash Testing
✅ Interruption Scenario Testing (calls, background, kill)
✅ Network Condition Testing


📂 Modules Tested (20 Modules)
#ModuleKey Scenarios1Onboarding / PaywallLanguage selection, subscriptions, restore purchase2PermissionsCamera, Photos, Local Network, ATT — Allow/Deny/Revoke3Print PhotosSingle/multi, HEIC, large files, B&W/color, layouts4Scan DocumentsAuto-crop, 24 pages max, reorder, poor lighting5Print DocumentsPDF, DOC, XLS, password-protected, corrupted, large files6Large Posters1/2/3-page grid, regression, resolution warning7Copy Live Text (OCR)Printed/handwritten, mixed language, edit before print8Web PagesIn-app browser, heavy pages, JS-heavy, offline9Labels4/8/12/24 per page, custom text, special characters10Passport PhotosCrop sizes, copies regression, image count regression11Clipboard PrintAuto-detect, empty state, long text12Drag & DropJPG/PDF/DOC/XLS, unsupported types, iPad split view13HistorySave entries, duplicates, re-print, clear14SettingsLanguage change, share button, lifetime access15Printer ConnectivityDiscovery, offline, busy/jam, multiple printers16Network ConditionsAirplane mode, weak Wi-Fi, VPN, subnet mismatch17Interruption ScenariosIncoming call, background, kill, lock screen, Stage Manager18Performance & StabilityCold start, memory, CPU on OCR, 30-min session19Localization & AccessibilityAll languages, RTL, Dynamic Type, VoiceOver, Dark Mode20Security & PrivacyATT denial, no data in logs, receipt validation

📊 Test Case Stats
PriorityCountDescriptionP025Critical — App-breaking bugsP145High — Core featuresP265Medium — Standard featuresP320Low — Edge cases & performanceP418UI polish & minor regressionsTotal150+

🐛 Key Bugs Found
Some critical issues identified and reported during testing:

TC-PAY-01 — Share button in Settings caused app crash (P0 Crash)
TC-WEB-01 — App crashed on printing heavy image-loaded web pages (P0 Crash)
TC-SCAN-01 — Scanning exactly 24 pages produced blank/empty output (P0 Crash)
TC-HIST-01 — Duplicate history entry created on app kill + reopen (P0 Regression)
TC-POST-04 — Grid lines remained visible after switching 2-page → 1-page poster (P2 Regression)
TC-PASS-01 — Copy count reset unexpectedly when changing passport photo size (P2 Regression)


📁 Files in This Project
FileDescriptionPrinter_App_Project.xlsxComplete test case suite with Pass/Fail status, steps, expected results

🛠️ Tools Used

TestFlight — Beta build installation
Xcode / Device Logs — Crash log analysis
Apple Network Link Conditioner — Network throttling
Figma — Design reference comparison
Excel — Test case documentation


🔗 References

App Design (Figma)


Part of Tanvi Sonani's iOS Manual QA Testing Portfolio
