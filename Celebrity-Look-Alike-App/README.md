# 🌟 Celebrity Look Alike App — iOS Manual QA Project

> **App:** Celebrity Look Alike — Face Match & Celebrity Twin  
> **Platform:** iOS (iPhone & iPad)  
> **Testing Period:** May 2025 – March 2026  
> **Tester:** Manual QA Tester (2 Years Experience)

---

## 📋 Project Summary

Complete manual QA testing project for an iOS celebrity face-matching application. This project covers functional, regression, permission, localization, ad flow, device, and edge case testing across 12 modules with 100+ test cases and 54+ bugs reported.

---

## 📱 Devices Tested

| Device | Type | OS | Screen | Key Issues Found |
|--------|------|----|--------|-----------------|
| iPhone 8 | Phone | iOS 15+ | 4.7" | Purchase screen cut from top; font size issues |
| iPhone XR | Phone | iOS 15+ | 6.1" | General flow testing; mid-range device |
| iPhone 11 | Phone | iOS 15+ | 6.1" | Purchase plan delay; rating button issues |
| iPhone 12 | Phone | iOS 18.5 | 6.1" | Primary device; video upload bug (iOS 18.5) |
| iPad | Tablet | iPadOS 15+ | 10.2"+ | Purchase screen cut; settings icons blurry |

---

## 🌐 Languages Tested

English · Spanish · Portuguese · Japanese

---

## 🧪 Testing Types Covered

- ✅ Manual Functional Testing
- ✅ Regression Testing
- ✅ Permission Testing (Camera, Gallery, Notifications, ATT)
- ✅ Ad Flow Testing (free/paid logic)
- ✅ Localization Testing (4 languages)
- ✅ Device Compatibility Testing (5 devices)
- ✅ Negative & Edge Case Testing
- ✅ Stability & Crash Testing
- ✅ Purchase & Paywall Testing

---

## 📂 Modules Tested (12 Modules)

| # | Module | Key Scenarios |
|---|--------|--------------|
| 1 | Onboarding / Intro Flow | 4 screens, swipe, dot indicator, review popup |
| 2 | Permissions | Camera, Gallery, Notifications, ATT — Allow/Deny |
| 3 | Home Screen | 3 feature cards, Settings, Crown icon navigation |
| 4 | Celebrity Look Alike | Photo picker, face validation, scanning, 3 match % |
| 5 | Make Me a Celebrity | M/F selection, scanning, result, paywall after 1st use |
| 6 | Celebrity Match | Combined celeb list, match %, side-by-side result, bio |
| 7 | Purchase / Paywall | Weekly/Yearly plans, free trial, restore purchase |
| 8 | Settings | Language select, Share, More Apps, Contact Us, Intro replay |
| 9 | Ads | Free 1st result, ad from 2nd, ad removal post-purchase |
| 10 | Review Popup | Intro screen 4, 2nd launch, star rating trigger |
| 11 | Localization | All 4 languages — UI + celebrity info |
| 12 | Edge Cases & Negative Tests | Network failure, large images, partial faces, crash prevention |

---

## 📊 Test Case & Bug Stats

### Test Cases
| Priority | Count |
|----------|-------|
| P1 (Critical) | ~80 |
| P2 (Medium) | ~20 |
| **Total** | **100+** |

### Bug Report Summary
| Category | Count |
|----------|-------|
| Total Bugs Reported | 54+ |
| P1 Critical Bugs | ~45 |
| P2 Medium Bugs | ~9 |
| App Crashes Found | 2 |
| Fixed | 40+ |
| Open / Next Version | 6 |

---

## 🐛 Key Bugs Found

### 💥 App Crashes
- **BUG-036** — App crashed when tapping Take Photo + Choose Photo simultaneously (P1 Crash)
- **BUG-037** — Multiple screens stacked when tapping 2 buttons at same time (P1 Crash)

### 🔴 Critical Bugs (P1)
- **BUG-002** — Yearly plan incorrectly showed 'Try For Free' button (P1)
- **BUG-005** — Rapid Next tapping caused text shuffle + page stuck in Onboarding (P1)
- **BUG-015** — Purchase screen cut from top on iPad (P1)
- **BUG-016** — Tapping Crown icon locked entire MMC result page (P1)
- **BUG-017** — No internet + Take Selfie caused silent failure — no alert, no scan (P1)
- **BUG-022** — Restore Purchase showed infinite loader after tapping OK (P1)
- **BUG-033** — Half-face in Take Photo showed empty result screen (P1)
- **BUG-039** — After offline → Try Again → reconnect: stuck in continuous scan loop (P1)
- **BUG-040** — Result screen shown twice (duplicate) after scan (P1)
- **BUG-049** — Video upload allowed instead of images only (iOS 18.5, iPhone 12) (P1)

### 🟡 Medium Bugs (P2)
- **BUG-001** — Slider UI shown on Intro Screen 3 with no function (P2)
- **BUG-009** — Emoji animation visible on result screen (should be scan only) (P2)
- **BUG-011** — 'Influence' watermark text appearing on downloaded/shared image (P2)
- **BUG-023** — Purchase plan boxes appeared with 2-3 second delay on iPhone 11 (P2)

---

## 📁 Files in This Project

| File | Description |
|------|-------------|
| `CelebLookAlike_QA_Portfolio.xlsx` | Complete test case suite, bug report log, and device coverage matrix |

---

## 🛠️ Tools Used

- **TestFlight** — Beta build installation & testing
- **Xcode / Device Logs** — Crash log analysis
- **Apple Network Link Conditioner** — Network throttling (2G, offline)
- **Excel** — Test case documentation & bug tracking
- **Figma** — Design reference for UI validation

---

## 📌 Notable Testing Highlights

- **iOS 18.5 specific bug found** — Video upload allowed in image picker (iPhone 12, BUG-049)
- **Multi-tap crash reproduced** — Simultaneous button taps caused app crash (BUG-036)
- **Ad logic fully tested** — Free/paid ad flow verified across all 3 features
- **4 languages tested** — Including Japanese; UI + celebrity info verified
- **5 devices covered** — From iPhone 8 (small screen) to iPad (large screen)
- **Purchase flow end-to-end** — Weekly, yearly, free trial, restore purchase all tested

---

*Part of iOS Manual QA Testing Portfolio — 30+ Apps Tested*
