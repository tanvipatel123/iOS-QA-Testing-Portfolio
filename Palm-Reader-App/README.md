# 🔮 Palm Reader App — iOS Manual QA Project

> **App:** Palm Reader — Astrology & Horoscope iOS App  
> **Platform:** iOS (iPhone & iPad)  
> **Testing Period:** May 2025 – April 2026  
> **Tester:** Manual QA Tester (2 Years Experience)

---

## 📋 Project Summary

Complete manual QA testing project for an iOS Astrology and Palm Reading application. This project covers functional, regression, localization, device compatibility, purchase flow, ad watch flow, and edge case testing across 12 modules with 150+ test cases and 115+ bugs reported.

---

## 📱 Devices Tested

| Device | Type | OS | Screen | Key Issues Found |
|--------|------|----|--------|-----------------|
| iPhone 8 | Phone | iOS 18 & 26 | 4.7" | Spanish layout issues; Date picker year cut |
| iPhone XR | Phone | iOS 18 & 26 | 6.1" | Date of birth year text cut; mid-range performance |
| iPhone 11 | Phone | iOS 18 & 26 | 6.1" | Rating alert 'Not Now' not tappable |
| iPhone 12 | Phone | iOS 18 & 26 | 6.1" | Primary device; most bugs reproduced here |
| iPad | Tablet | iPadOS 18 | 10.2"+ | Location not tappable; scanner UI broken; ad watch UI broken |

---

## 🌐 Languages Tested

English · Spanish · Russian

---

## 🧪 Testing Types Covered

- ✅ Manual Functional Testing
- ✅ Regression Testing
- ✅ Localization Testing (3 languages)
- ✅ Device Compatibility Testing (5 devices)
- ✅ Purchase & StoreKit Flow Testing
- ✅ Ad Watch Flow Testing
- ✅ Permission Testing (Camera, Location, Notifications)
- ✅ API & Network Testing
- ✅ Edge Case & Negative Testing
- ✅ App Update / Migration Testing
- ✅ Stability & Crash Testing

---

## 📂 Modules Tested (12 Modules)

| # | Module | Key Scenarios |
|---|--------|--------------|
| 1 | App Install & Intro Flow | Notification permission, onboarding screens, intro navigation |
| 2 | Palm Scan & Analysis | Left/right scan, animation, palm line drawing, error handling |
| 3 | Personalize / Onboarding Flow | Name, gender, DOB, time, location, relationship status |
| 4 | Tab Bar Navigation | 4 tabs: Horoscope, Palm Reader, Compatibility, Birth Chart |
| 5 | Horoscope Screen | API logic, loader behavior, locked state, date navigation |
| 6 | Compatibility Screen | Multi-user, locked state, static data, partner selection |
| 7 | Birth Chart Screen | Natal chart, sun/moon/ascendant signs, data consistency |
| 8 | In-App Purchase | Weekly/Monthly/Yearly/Lifetime, StoreKit, refund, price consent |
| 9 | Ad Watch Flow | Ad load, unlock logic, session behavior, network failure |
| 10 | User Profile Management | Create/edit/delete, multiple profiles, data update logic |
| 11 | Localization | Spanish, Russian — UI labels, date formats, API content |
| 12 | Edge Cases & Negative Testing | Network, data consistency, UI/UX, performance, memory |

---

## 📊 Test Case & Bug Stats

### Test Cases
| Priority | Count |
|----------|-------|
| P1 Critical | ~140 |
| P2 Medium | ~10 |
| **Total** | **150+** |

### Bug Report Summary
| Category | Count |
|----------|-------|
| Total Bugs Reported | 115+ |
| P1 Critical Bugs | ~105 |
| P2 Medium Bugs | ~10 |
| Fixed | 70+ |
| Open / Not Solved | 6 |
| Won't Fix | 1 |

---

## 🐛 Key Bugs Found

### 💥 Critical Crashes & Blockers
- **BUG-033** — App crashed when tapping delete icon multiple times rapidly (P1 Crash)
- **BUG-042** — Splash screen stuck when offline during profile creation (P1)
- **BUG-044** — App stuck on splash after closing palm scan during intro (P1)
- **BUG-073** — Loader spins forever after turning off internet post profile creation (P1)

### 🔴 Major Bugs (P1)
- **BUG-010** — Duplicate profile with same data was allowed (P1)
- **BUG-012** — Lifetime plan button wrong label + not tappable (P1)
- **BUG-016** — Device language Spanish — app defaulted to English on install (P1 — Not Solved)
- **BUG-019** — 'Use Current Location' not tappable on iPad first install (P1 — Not Solved)
- **BUG-024** — Manual zodiac sign not saved; DOB sign overrides after edit (P1)
- **BUG-034** — Gender screen back navigation always reset to Male (P1)
- **BUG-036** — Location current location + text field caused infinite loader (P1)
- **BUG-051** — App stuck on scan screen after update from old version (P1)
- **BUG-056** — Natal Chart and Planets screen showed different percentages (P1)
- **BUG-057** — 'Other' gender profile caused infinite loading in compatibility (P1)
- **BUG-059** — Push notifications not delivered; only badge count shown (P1 — Open)
- **BUG-065** — Delete icon logic wrong after subscription expires (P1)

### 🟡 Medium Bugs (P2)
- **BUG-001** — Palm data percentage refreshed randomly every time screen viewed (P2 — Open)
- **BUG-076** — Numerology lucky number animation stopped after app backgrounded (P2 — Open)

---

## 📁 Files in This Project

| File | Description |
|------|-------------|
| `Palm_Reader_Whole_Project.xlsx` | Complete test case suite, bug report log, and device coverage matrix |

---

## 🛠️ Tools Used

- **TestFlight** — Beta build installation & testing
- **Xcode / Device Logs** — Crash log analysis
- **Apple Network Link Conditioner** — Network throttling & offline testing
- **Charles Proxy** — API monitoring & network request inspection
- **Excel** — Test case documentation & bug tracking

---

## 🎥 App Demo

- [App Demo Video](https://drive.google.com/file/d/1Aob6suPRToJoNUCNoJjmo-amXQgT6YyF/view?usp=drive_link)

---

## 📌 Notable Testing Highlights

- **App update migration tested** — Old version data carry-over verified after update
- **StoreKit refund tested** — Verified features re-lock correctly after refund
- **API caching logic tested** — Same zodiac sign reuses cached API response verified
- **3 languages tested** — English, Spanish, Russian; UI + API content verified in all
- **5 devices covered** — From iPhone 8 (small/old) to iPad (large screen)
- **Offline + purchase flow** — Ad banner removal, feature locking after refund all tested

---

*Part of iOS Manual QA Testing Portfolio — 30+ Apps Tested*
