# AYSLife

**All-in-one personal life app for Android** by **AYS Soft**.

AYSLife brings several everyday tools together in one app, so you don't need a separate app for each of them.

## Modules

- **Habit tracker** — build and track daily habits
- **Finances** — track income and expenses
- **Shopping list** — plan your shopping
- **Calories** — log meals and calories, including food recognition from photos
- **Reflection journal** — daily notes and reflections
- **Planner** — tasks and schedule
- **Путь (The Way)** — break big goals into small, achievable steps with AI

Available in 7 languages: English, Russian, Ukrainian, Polish, German, Czech, Hungarian.

## Privacy

- All your data is stored **locally on your device** (SQLite), with optional **encrypted backups**.
- There is no developer server and no account.
- AI features are optional. They use **your own Google Gemini API key** and send requests directly to Google.

## Download

➡️ [Download the latest APK](../../releases/latest)

To install, open the downloaded `.apk` on your Android phone and allow installation from unknown sources if asked.

## Status

- Version **1.0.0** — first public release
- Google Play publication — in progress

## Tech

- **Expo SDK 58 / React Native 0.88** (React 19, New Architecture) — Android-only, written in **TypeScript**
- **Expo Router** for file-based navigation, **Zustand** for state, custom UI components with Reanimated
- **Offline-first storage:** `expo-sqlite` with migrations, `expo-secure-store` for secrets, encrypted backups (`@noble/ciphers` + `fflate`)
- **AI features via Google Gemini API** (user's own key, no backend) — goal breakdown, food-photo analysis, voice-to-text
- **i18n:** 7 languages with i18next
- **Builds:** EAS Build (APK / AAB profiles) or local Gradle release build
- Developed with an AI-assisted workflow (Claude Code)

---

### 🇵🇱 Po polsku

**AYSLife** to aplikacja na Androida łącząca kilka codziennych narzędzi w jednym miejscu: nawyki, finanse, lista zakupów, kalorie, dziennik refleksji, planer oraz moduł „Путь” do dzielenia celów na kroki z pomocą AI. Dane przechowywane są lokalnie na urządzeniu. Funkcje AI są opcjonalne i działają z Twoim własnym kluczem Google Gemini.

---

© AYS Soft
