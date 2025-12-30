# 📅 Alevi.app Calendar & Timekeeping Logic

Alevi.app does not use a static database for religious dates. It calculates them algorithmically based on the Anatolian "Halk Takvimi" (Folk Calendar) and lunar cycles.

## ❄️ Hızır Fasting Calculation
Unlike modern calendars, the Hızır Fasting (Hızır Orucu) is tied to the transition between "Zemheri" (Deep Winter) and "Hızır Günleri".
- **Rule:** The fasting starts in the second week of February.
- **Logic:** Our algorithm converts Gregorian dates to the traditional Rumi (Julian-based) system to ensure historical accuracy with 800-year-old traditions.

## 🌙 Muharram & Yas-ı Matem
- Calculated using the Hijri (Lunar) calendar with a high-precision lunar-cycle algorithm.
- Synchronized with the official declarations of the canonical Alevi institutions.

## ☀️ Solar Events (Nevruz & Gündönümü)
Calculated based on astronomical equinox data to determine the exact moment of "Sultan Nevruz".
