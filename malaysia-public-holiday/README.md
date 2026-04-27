# Malaysia Holiday Data Files 🇲🇾

Complete data package for MyHoliday Planner MY app.

## Files

| File | Description | Size |
|------|-------------|------|
| `2025.json` | Malaysia public holidays 2025 (same format as your 2026.json) | Federal + state, exclude_states |
| `school_holidays_2026.json` | KPM school calendar — Group A & B term dates | From MOE official release |
| `holiday_info.json` | Holiday descriptions in EN/BM/ZH/TA + greetings + traditions | 20 holidays covered |
| `lunar_calendar.json` | Chinese lunar month data 2025–2028 + festivals + prayer days | Verified astronomical data |
| `states_meta.json` | 16 states — codes, capitals, rulers, weekends, school groups | Includes replacement holiday rules |
| `locale_en.json` | English UI strings | Full app coverage |
| `locale_ms.json` | Bahasa Melayu UI strings | Full app coverage |
| `locale_zh.json` | 简体中文 UI strings + lunar terms | Full app coverage |

## Data Sources & Verification

- **Public holidays**: Cross-referenced with gazette.gov.my, timeanddate.com, Wikipedia
- **School holidays**: From KPM official academic calendar 2026 (moe.gov.my)
- **Lunar calendar**: Verified against Hong Kong Observatory astronomical data
- **State metadata**: From state government official websites
- **Weekend rules**: Johor changed back to Sat-Sun on 1 Jan 2025 (verified)

## Important Notes

1. **Johor weekend change**: Starting 1 Jan 2025, Johor reverted from Fri-Sat to Sat-Sun. Your existing `2026.json` on GitHub still lists Johor as Fri-Sat — this should be corrected.

2. **Islamic holiday dates**: Dates for Hari Raya, Nuzul Al-Quran, etc. are based on astronomical predictions and may shift by 1-2 days based on moon sighting. The app should handle updates via the weekly sync.

3. **School holidays**: Two groups — Group A (Kedah, Kelantan, Terengganu) starts 1 day earlier than Group B due to Friday-Saturday weekends.

4. **Lunar data coverage**: Covers 2025-2028 (4 years). Extend by adding more entries to `lunar_months` array.

## How to Host

Upload all files to your GitHub Pages:

```
https://seekm79.github.io/share/malaysia-public-holiday/2025.json
https://seekm79.github.io/share/malaysia-public-holiday/2026.json
https://seekm79.github.io/share/malaysia-public-holiday/school_holidays_2026.json
https://seekm79.github.io/share/malaysia-public-holiday/holiday_info.json
https://seekm79.github.io/share/malaysia-public-holiday/lunar_calendar.json
https://seekm79.github.io/share/malaysia-public-holiday/states_meta.json
https://seekm79.github.io/share/malaysia-public-holiday/locale_en.json
https://seekm79.github.io/share/malaysia-public-holiday/locale_ms.json
https://seekm79.github.io/share/malaysia-public-holiday/locale_zh.json
```
