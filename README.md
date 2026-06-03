# 🥗 Calorie Tracker

A simple, free calorie and weight tracking web app. No account needed — just open the link and start logging.

**Live app → [andos80.github.io/calorie-tracker](https://andos80.github.io/calorie-tracker/)**

---

## Features

### 📅 Today
- Log meals from the built-in food library or enter them manually
- Choose from **70+ common foods** with smart units (pcs, glass, slice, tbsp, cl, g)
- See your daily calorie total vs. your personal goal with a progress bar
- Macro breakdown: Protein, Carbs and Fat
- Navigate to any past or future date using the arrow buttons

### 💧 Water Tracker
- Track your daily water intake with quick-add buttons (+1 glass, +33 cl, +50 cl)
- Visual progress bar and glass icons
- Custom amount input for any size

### 🔍 Search Food
- Browse the built-in library by category (Eggs & Dairy, Meat & Fish, Bread & Grains, Vegetables, Fruits, Drinks, Snacks & Other)
- Filter by typing in the search bar
- **Search online** via the Open Food Facts database for any food not in the library
- Click a result → enter grams → log it to today

### 📆 Calendar
- Full monthly calendar view showing calories logged per day
- Green = under goal · Red = over goal · Outlined = today
- Tap any day to jump straight to logging for that date

### ⚖️ Weight
- Log your weight once a week (or as often as you like)
- Set an optional goal weight
- Stats: starting weight, current weight, total change, goal
- Line chart with 1M / 3M / 6M / All time views
- Full history with change since last entry

### 📊 History
- Bar chart of daily calories for the last 7, 14 or 30 days
- Green bars = under goal · Red bars = over goal
- Dashed goal line for reference

---

## Food Library

Over 70 everyday foods across 7 categories with accurate calorie and macro data (per 100g). Units are set automatically per food type:

| Unit | Examples |
|------|---------|
| pcs | Eggs, sausage, apple, banana, avocado |
| glass | Milk, juice, Coca-Cola, smoothie |
| cl | Beer, wine |
| slice | Bread, ham, bacon |
| tbsp | Butter, peanut butter, olive oil, mayo |
| cup | Coffee |
| g | Chicken, beef, fish, rice, pasta, cheese, vegetables |

---

## Saving Your Data

All data is stored in your browser's local storage — nothing is sent to a server.

**To back up or move your data:**
1. Go to the **Today** tab and scroll to the bottom
2. Click **⬇ Export** — saves a `.json` file to your device
3. On any device, click **⬆ Import** and select your file to restore everything

Each person keeps their own `.json` file. The backup includes meals, water, weight entries and all settings.

---

## How to Use

1. Open **[andos80.github.io/calorie-tracker](https://andos80.github.io/calorie-tracker/)** in any browser
2. Set your daily calorie goal in the top-right corner
3. Log meals on the **Today** tab using the library dropdown or the manual form
4. Track water intake in the **💧 Water** section
5. Check the **Calendar** for a monthly overview
6. Log your weight weekly on the **Weight** tab
7. Export your data regularly to keep a backup

Works on desktop and mobile. No installation, no account, no ads.

---

## Tech

- Pure HTML, CSS and JavaScript — single file, no frameworks, no build step
- Data stored in `localStorage` as JSON
- Food search powered by [Open Food Facts](https://world.openfoodfacts.org/) (open-source food database)
- Charts by [Chart.js](https://www.chartjs.org/)
- Hosted for free on [GitHub Pages](https://pages.github.com/)
