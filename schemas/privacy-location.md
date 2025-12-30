# 📍 Privacy-First Location Logic (The "Can" Protocol)

Standard apps track your GPS coordinates. **Alevi.app does NOT.** ## 🛡️ How it works:
1. **Manual Selection:** The user selects a city/region manually.
2. **Local Processing:** The coordinates of the selected city are stored locally in `UserDefaults`.
3. **No Backend Sync:** Location data is never sent to a server. 
4. **Offline Ephemeris:** Solar calculations (Sunrise/Sunset for Çerağ) are performed on-device using a mathematical formula, not an external API.

This ensures that a user's ritualistic habits and physical location are never profiled or sold.
