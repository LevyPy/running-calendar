# To-dos:

- [ ] Telas do Fenix -> 
- [ ] Norma 7 cBAT
- [ ] Norma 240 World Athletics

# 🏃‍♂️ Running Calendar Repository

*A personal repository for tracking races, goals, and running statistics*

## 📑 Repository Structure

- [**RACES.md**](./RACES.md) - Upcoming, registered, and completed races
- [**GOALS.md**](./GOALS.md) - Performance goals and personal records
- [**STATS.md**](./STATS.md) - Running statistics and analytics
- [**GARMIN.md**](./GARMIN.md) - Garmin device configurations

## 🚀 Quick Navigation

### 📅 Race Management

- [View upcoming races](./RACES.md#-upcoming-races)
- [View registered races](./RACES.md#-registered-races)
- [View completed races](./RACES.md#-completed-races)

### 🎯 Performance Tracking

- [View 5K goals](./GOALS.md#-distance-based-goals)
- [View 10K goals](./GOALS.md#-distance-based-goals)
- [View half marathon goals](./GOALS.md#-distance-based-goals)
- [View personal records](./GOALS.md#-personal-records)

### 📊 Statistics

- [View annual summary](./STATS.md#-annual-distance-summary)
- [View race distribution](./STATS.md#-race-category-distribution)
- [View year-over-year progress](./STATS.md#-year-over-year-improvement)

### ⌚ Garmin Setup

- [View device configurations](./GARMIN.md#-device-specific-configurations)

## 📂 Folder Structure

```
running-calendar/
├── garmin/
│   ├── fenix_3/
│   │   ├── data_fields.md
│   │   ├── data_screen_run.md
│   │   └── data_screen_trail_run.md
│   ├── forerunner_745/
│   │   ├── data_fields.md
│   │   ├── data_screen_run.md
│   │   └── data_screen_trail_run.md
│   ├── img/
│   └── configs.md
├── garmin.md       # Garmin settings and data screen preferences
├── goals.md        # Running goals, targets, and achievements
├── races.md        # Calendar view: upcoming & potential races (+ status)
├── history.md      # Log of completed races with results and details
├── stats.md        # Yearly stats: distance, sessions, PRs, etc.
└── README.md       # Repository overview and usage instructions
```

## 🛠️ How to Update

### Adding a New Race

1. Open [RACES.md](./RACES.md)
2. Add the race to the appropriate section:
   - **Upcoming Races**: For races you're considering
   - **Registered Races**: For races you've officially registered for
3. Follow the existing table format

### Updating Race Status

1. When you register for a race:
   - Move it from "Upcoming" to "Registered" section
   - Add registration details

2. After completing a race:
   - Remove from "Registered" section
   - Add to "Completed Races" under the correct year
   - Fill in all race details (time, placement, etc.)
   - Update [STATS.md](./STATS.md) with new race data

### Setting New Goals

1. Open [GOALS.md](./GOALS.md)
2. Add or update goals in the appropriate distance section
3. Use 🎯 for targets and ✅ for achieved goals

### Updating Personal Records

1. When you set a new PR:
   - Update the PR table in [GOALS.md](./GOALS.md)
   - Update year-over-year progress in [STATS.md](./STATS.md)

## 💡 Maintenance Best Practices

1. **Regular Updates**:
   - Update race results immediately after each race
   - Review and update goals quarterly
   - Update statistics monthly or after significant races

2. **Yearly Maintenance**:
   - At the end of each year, create a new year section in the completed races
   - Archive old races by keeping them in the collapsible sections
   - Set new goals for the upcoming year

3. **Backup**:
   - Regularly commit changes to keep history
   - Consider creating yearly branches for long-term archiving

4. **Visual Consistency**:
   - Maintain consistent formatting across all files
   - Use emojis consistently for visual cues
   - Keep tables aligned for better readability

---

*Last updated: August 2024*
