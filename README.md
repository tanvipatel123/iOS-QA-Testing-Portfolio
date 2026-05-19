# 🖨️ Air Printer App — iOS Manual QA Project

> **App:** Air Printer — AirPrint for iPhone & iPad  
> **Platform:** iOS (iPhone & iPad)  
> **Tester:** Tanvi Sonani  
> **Testing Period:** July 2024 – Ongoing  

---

## 📋 Project Summary

Complete manual QA testing project for an iOS AirPrint printing application. This project covers end-to-end functional, regression, performance, security, localization, and accessibility testing across 20 modules and 150+ test cases.

---

## 📱 Devices Tested

| Device | OS |
|--------|----|
| iPhone SE | iOS |
| iPhone 12 | iOS |
| iPhone 14 Pro | iOS |
| iPhone 15 Pro Max | iOS |
| iPad (9th Gen) | iPadOS |

---

## 🌐 Languages Tested

English · Hindi · French · Spanish · German · Arabic (RTL)

---

## 🧪 Testing Types Covered

- ✅ Manual Functional Testing
- ✅ Regression Testing
- ✅ Permission Testing
- ✅ Performance Testing
- ✅ Localization & RTL Testing
- ✅ Accessibility Testing (VoiceOver, Dynamic Type)
- ✅ Security & Privacy Testing
- ✅ Crash Testing
- ✅ Interruption Scenario Testing (calls, background, kill)
- ✅ Network Condition Testing

---

## 📂 Modules Tested (20 Modules)

| # | Module | Key Scenarios |
|---|--------|--------------|
| 1 | Onboarding / Paywall | Language selection, subscriptions, restore purchase |
| 2 | Permissions | Camera, Photos, Local Network, ATT — Allow/Deny/Revoke |
| 3 | Print Photos | Single/multi, HEIC, large files, B&W/color, layouts |
| 4 | Scan Documents | Auto-crop, 24 pages max, reorder, poor lighting |
| 5 | Print Documents | PDF, DOC, XLS, password-protected, corrupted, large files |
| 6 | Large Posters | 1/2/3-page grid, regression, resolution warning |
| 7 | Copy Live Text (OCR) | Printed/handwritten, mixed language, edit before print |
| 8 | Web Pages | In-app browser, heavy pages, JS-heavy, offline |
| 9 | Labels | 4/8/12/24 per page, custom text, special characters |
| 10 | Passport Photos | Crop sizes, copies regression, image count regression |
| 11 | Clipboard Print | Auto-detect, empty state, long text |
| 12 | Drag & Drop | JPG/PDF/DOC/XLS, unsupported types, iPad split view |
| 13 | History | Save entries, duplicates, re-print, clear |
| 14 | Settings | Language change, share button, lifetime access |
| 15 | Printer Connectivity | Discovery, offline, busy/jam, multiple printers |
| 16 | Network Conditions | Airplane mode, weak Wi-Fi, VPN, subnet mismatch |
| 17 | Interruption Scenarios | Incoming call, background, kill, lock screen, Stage Manager |
| 18 | Performance & Stability | Cold start, memory, CPU on OCR, 30-min session |
| 19 | Localization & Accessibility | All languages, RTL, Dynamic Type, VoiceOver, Dark Mode |
| 20 | Security & Privacy | ATT denial, no data in logs, receipt validation |

---

## 📊 Test Case Stats

| Priority | Count | Description |
|----------|-------|-------------|
| P0 | 25 | Critical — App-breaking bugs |
| P1 | 45 | High — Core features |
| P2 | 65 | Medium — Standard features |
| P3 | 20 | Low — Edge cases & performance |
| P4 | 18 | UI polish & minor regressions |
| **Total** | **150+** | |

---

## 🐛 Key Bugs Found

- **TC-PAY-01** — Share button in Settings caused app crash (P0 Crash)
- **TC-WEB-01** — App crashed on printing heavy image-loaded web pages (P0 Crash)
- **TC-SCAN-01** — Scanning exactly 24 pages produced blank/empty output (P0 Crash)
- **TC-HIST-01** — Duplicate history entry created on app kill + reopen (P0 Regression)
- **TC-POST-04** — Grid lines remained visible after switching 2-page → 1-page poster (P2 Regression)
- **TC-PASS-01** — Copy count reset unexpectedly when changing passport photo size (P2 Regression)

---

## 📁 Files in This Project

| File | Description |
|------|-------------|
| `Printer_App_Project.xlsx` | Complete test case suite with Pass/Fail status, steps, expected results |

---

## 🛠️ Tools Used

- **TestFlight** — Beta build installation
- **Xcode / Device Logs** — Crash log analysis
- **Apple Network Link Conditioner** — Network throttling
- **Figma** — Design reference comparison
- **Excel** — Test case documentation

---

## 🔗 References

- [App Design (Figma)](https://www.figma.com/design/UeeevXLzjpVCSmkNSAbFIP/Air-Printer-App)

---

*Part of Tanvi Sonani's iOS Manual QA Testing Portfolio*
