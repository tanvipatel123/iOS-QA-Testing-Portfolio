🔮 Palm Reader App — iOS Manual QA Project

App: Palm Reader — Astrology & Horoscope iOS App
Platform: iOS (iPhone & iPad)
Testing Period: May 2025 – April 2026
Tester: Manual QA Tester (2 Years Experience)


📋 Project Summary
Complete manual QA testing project for an iOS Astrology and Palm Reading application. This project covers functional, regression, localization, device compatibility, purchase flow, ad watch flow, and edge case testing across 12 modules with 150+ test cases and 115+ bugs reported.

📱 Devices Tested
DeviceTypeOSScreenKey Issues FoundiPhone 8PhoneiOS 18 & 264.7"Spanish layout issues; Date picker year cutiPhone XRPhoneiOS 18 & 266.1"Date of birth year text cut; mid-range performanceiPhone 11PhoneiOS 18 & 266.1"Rating alert 'Not Now' not tappableiPhone 12PhoneiOS 18 & 266.1"Primary device; most bugs reproduced hereiPadTabletiPadOS 1810.2"+Location not tappable; scanner UI broken; ad watch UI broken

🌐 Languages Tested
English · Spanish · Russian

🧪 Testing Types Covered

✅ Manual Functional Testing
✅ Regression Testing
✅ Localization Testing (3 languages)
✅ Device Compatibility Testing (5 devices)
✅ Purchase & StoreKit Flow Testing
✅ Ad Watch Flow Testing
✅ Permission Testing (Camera, Location, Notifications)
✅ API & Network Testing
✅ Edge Case & Negative Testing
✅ App Update / Migration Testing
✅ Stability & Crash Testing


📂 Modules Tested (12 Modules)
#ModuleKey Scenarios1App Install & Intro FlowNotification permission, onboarding screens, intro navigation2Palm Scan & AnalysisLeft/right scan, animation, palm line drawing, error handling3Personalize / Onboarding FlowName, gender, DOB, time, location, relationship status4Tab Bar Navigation4 tabs: Horoscope, Palm Reader, Compatibility, Birth Chart5Horoscope ScreenAPI logic, loader behavior, locked state, date navigation6Compatibility ScreenMulti-user, locked state, static data, partner selection7Birth Chart ScreenNatal chart, sun/moon/ascendant signs, data consistency8In-App PurchaseWeekly/Monthly/Yearly/Lifetime, StoreKit, refund, price consent9Ad Watch FlowAd load, unlock logic, session behavior, network failure10User Profile ManagementCreate/edit/delete, multiple profiles, data update logic11LocalizationSpanish, Russian — UI labels, date formats, API content12Edge Cases & Negative TestingNetwork, data consistency, UI/UX, performance, memory

📊 Test Case & Bug Stats
Test Cases
PriorityCountP1 Critical~140P2 Medium~10Total150+
Bug Report Summary
CategoryCountTotal Bugs Reported115+P1 Critical Bugs~105P2 Medium Bugs~10Fixed70+Open / Not Solved6Won't Fix1

🐛 Key Bugs Found
💥 Critical Crashes & Blockers

BUG-033 — App crashed when tapping delete icon multiple times rapidly (P1 Crash)
BUG-042 — Splash screen stuck when offline during profile creation (P1)
BUG-044 — App stuck on splash after closing palm scan during intro (P1)
BUG-073 — Loader spins forever after turning off internet post profile creation (P1)

🔴 Major Bugs (P1)

BUG-010 — Duplicate profile with same data was allowed (P1)
BUG-012 — Lifetime plan button wrong label + not tappable (P1)
BUG-016 — Device language Spanish — app defaulted to English on install (P1 — Not Solved)
BUG-019 — 'Use Current Location' not tappable on iPad first install (P1 — Not Solved)
BUG-024 — Manual zodiac sign not saved; DOB sign overrides after edit (P1)
BUG-034 — Gender screen back navigation always reset to Male (P1)
BUG-036 — Location current location + text field caused infinite loader (P1)
BUG-051 — App stuck on scan screen after update from old version (P1)
BUG-056 — Natal Chart and Planets screen showed different percentages (P1)
BUG-057 — 'Other' gender profile caused infinite loading in compatibility (P1)
BUG-059 — Push notifications not delivered; only badge count shown (P1 — Open)
BUG-065 — Delete icon logic wrong after subscription expires (P1)

🟡 Medium Bugs (P2)

BUG-001 — Palm data percentage refreshed randomly every time screen viewed (P2 — Open)
BUG-076 — Numerology lucky number animation stopped after app backgrounded (P2 — Open)


📁 Files in This Project
FileDescriptionPalm_Reader_Whole_Project.xlsxComplete test case suite, bug report log, and device coverage matrix

🛠️ Tools Used

TestFlight — Beta build installation & testing
Xcode / Device Logs — Crash log analysis
Apple Network Link Conditioner — Network throttling & offline testing
Charles Proxy — API monitoring & network request inspection
Excel — Test case documentation & bug tracking


🎥 App Demo

App Demo Video


📌 Notable Testing Highlights

App update migration tested — Old version data (sun sign, palm data) carry-over verified after update
StoreKit refund tested — Verified features re-lock correctly after refund via StoreKit
API caching logic tested — Verified same zodiac sign reuses cached API response (no duplicate call)
3 languages tested — English, Spanish, Russian; UI + API content verified in all
5 devices covered — From iPhone 8 (small/old) to iPad (large screen)
Offline + purchase flow — Ad banner removal, feature locking after refund all tested


Part of iOS Manual QA Testing Portfolio — 30+ Apps Tested
