# 🥗 Calorie Tracker

A free, privacy-first calorie and weight tracking web app. No account, no install, no ads — just open the link and start logging.

**Live app → [andos80.github.io/calorie-tracker](https://andos80.github.io/calorie-tracker/)**

---

## Features

### 📅 Today
- Set your daily calorie goal and track progress with a gradient progress bar
- Log meals from the built-in food library using a dropdown with **75+ common foods**
- Smart units per food type — eggs in pcs, milk in glasses, bread in slices, beer in cl, etc.
- Add any meal manually with full macro breakdown (protein, carbs, fat)
- Navigate to any past or future date with the arrow buttons
- Export and import your personal data as a `.json` backup file

### 💧 Water Tracker
- Quick-add buttons: **+1 glass**, **+33 cl**, **+50 cl**, or enter any custom amount
- Visual progress bar and animated water drop icons
- Daily goal of 2000 ml, resets automatically each day

### 🔍 Search Food
- Browse the built-in library by category with filter chips
- Real-time search filters the library as you type
- **Search online** via [Open Food Facts](https://world.openfoodfacts.org/) for anything not in the library
- Select a result → enter grams → log it to today in one tap

### 📆 Calendar
- Full monthly calendar showing calories logged for every day
- 🟢 Green = under goal · 🔴 Red = over goal · Outlined cell = today
- Navigate between months with the arrow buttons
- Tap any day to jump straight to logging for that date

### ⚖️ Weight
- Log your weight as often as you like (recommended: once a week)
- Set an optional goal weight to track progress towards
- Stats summary: starting weight · current weight · total change · goal
- Smooth line chart with **1M / 3M / 6M / All time** period views
- Full history list showing the change since each previous entry

### 📊 History
- Bar chart of daily calorie totals for the last **7, 14 or 30 days**
- Bars turn red on days you went over goal
- Dashed goal line for easy visual reference

### 🌙 Dark Mode
- Toggle between light and dark with the button in the top corner
- Deep navy dark theme, easy on the eyes
- Preference is saved and restored automatically

---

## Food Library

**75+ everyday foods** across 7 categories with accurate calorie and macro data. Units are set automatically per food:

| Unit | Examples |
|------|---------|
| **pcs** | Egg, sausage, bagel, tortilla, apple, banana, orange, avocado, carrot, tomato |
| **glass** | Milk, orange juice, apple juice, Coca-Cola, smoothie |
| **cl** | Beer (lager), Beer (strong/IPA), Wine (red/white/rosé) |
| **slice** | White bread, whole wheat bread, ham, bacon |
| **tbsp** | Butter, cream cheese, peanut butter, olive oil, ketchup, mayo, hummus |
| **cup** | Coffee (black), coffee with milk |
| **scoop** | Ice cream |
| **g** | Chicken, beef, fish, salmon, tuna, rice, pasta, oats, cheese, all vegetables |

### Categories
Eggs & Dairy · Meat & Fish · Bread & Grains · Vegetables · Fruits · Drinks · Snacks & Other

---

## Saving Your Data

All data is stored in your browser's **local storage** — nothing is ever sent to a server.

**To back up or move your data to another device:**
1. Go to the **Today** tab and scroll down to the **Your data** card
2. Tap **⬇ Export** — downloads a `calorie-tracker-YYYY-MM-DD.json` file
3. On any browser or device, tap **⬆ Import** and select your file to restore everything instantly

The backup includes all meals, water intake, weight entries, your calorie goal and water goal.
Each person keeps their own file — this is how multiple people can use the same app independently.

---

## How to Use

1. Open **[andos80.github.io/calorie-tracker](https://andos80.github.io/calorie-tracker/)** in any browser
2. On the **Today** tab, set your daily calorie goal and tap **Save**
3. Log meals using the **Add from library** dropdown, or fill in the manual form below it
4. Log water intake in the **💧 Water intake** section
5. Switch to **Weight** to start tracking your weekly weigh-ins
6. Use **Calendar** for a monthly overview — tap any day to edit it
7. Check **History** to see your calorie trend over time
8. Tap **⬇ Export** regularly to keep a personal backup

---

## Design & Compatibility

- Clean, premium design using the **Inter** typeface
- Full **dark mode** support
- Tested and optimised for **mobile** (iPhone/Android) and desktop
- Works in any modern browser — Chrome, Safari, Firefox, Edge

---

## Tech

- Single HTML file — no framework, no build step, no dependencies to install
- Data stored in `localStorage` as JSON (no server, no account)
- Food search powered by [Open Food Facts](https://world.openfoodfacts.org/) (open-source food database)
- Charts rendered by [Chart.js](https://www.chartjs.org/)
- Fonts from [Google Fonts](https://fonts.google.com/) (Inter)
- Hosted for free on [GitHub Pages](https://pages.github.com/)
