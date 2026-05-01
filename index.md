# GOHelper — User Manual

Welcome to GOHelper! This tool is designed to help you build complex search strings and prepare for boss battles in your mobile collection game without needing to memorize complicated syntax. 

Here is everything you need to know to get the most out of the app.

---

## 1. The Live Query Bar
At the top of the screen (just below the app bar) sits the **Live Query Bar**. This is the heart of the app.
* As you tap filters in the tabs below, you will see your search string magically build itself here.
* If your string gets too long to read, simply **tap the bar to expand it**.
* Once your string is ready, tap the **Copy** icon next to it. You can now paste this directly into your game's search bar.
* Use the **Backspace / Delete** icon to instantly clear all selected filters and start fresh.

---

## 2. Using Filters (Include vs. Exclude)
The app is divided into different tabs (General, Tags, Types, Stats, etc.). Inside these tabs are visual chips representing search terms.

* **To INCLUDE a term:** Tap a chip once. It will turn blue. (e.g., tapping `Shiny` will add `shiny` to your string).
* **To EXCLUDE a term:** **Long-press** a chip. It will turn red with a block icon. (e.g., long-pressing `Shiny` will add `!shiny` to your string, meaning "Find everything that is NOT shiny").
* **Chaining:** The app automatically handles the formatting. If you tap `Shiny` and `Lucky`, it generates `shiny&lucky` (which finds monsters that are BOTH shiny and lucky).

---

## 3. Saving & Managing Presets
If you build a search string that you use often (like a "Community Day Cleanup" or a "Trade List" string), you can save it!

1. Build your string using the filters.
2. Tap the large **Save Preset** button floating at the bottom of the screen.
3. Give your preset a memorable name (e.g., "Transfer Trash").
4. To access it later, tap the **Bookmark icon** at the top right of the screen.
5. In the Presets screen, you can copy your saved strings instantly, swipe to delete them, or tap the edit icon to tweak the string directly.

---

## 4. Custom Tags
Games often let you create your own custom tags (e.g., "BaseDefenders", "ToUpgrade"). GOHelper lets you integrate these into your search strings.

1. Go to the **Tags** tab.
2. Scroll to the bottom to the "Custom Tags" section.
3. Type the exact name of your in-game tag and tap **Save Tag**.
4. Your custom tag will now appear as a clickable chip at the top of the Tags tab. You can include or exclude it just like any other filter!

---

## 5. Type Weaknesses (The Types Tab)
The Types tab has special logic to help you find counters:

* **Type (`<type`):** Finds monsters that are **weak to** that type. (e.g., `<fire` finds Grass, Bug, Ice, and Steel types).
* **Moves (`>type`):** Finds monsters that **know a move** of that type. (e.g., `>fire` finds any monster that currently knows a Fire-type move, regardless of the monster's own typing).

---

## 6. Stat Ranges (The Stats Tab)
Instead of guessing CP or HP ranges, use the Stats tab to define exact numbers:

* **Min/Max CP & HP:** Enter a minimum and maximum to find a range (e.g., `cp500-1500`). If you only enter a minimum, it finds everything *above* that number. If you only enter a maximum, it finds everything *below* it.
* **Appraisal (0-4):** This filters by the exact Individual Value (IV) rating of Attack, Defense, or HP. Note that 0-4 refers to the *star rating* of that specific stat, not the raw number. `4` means a perfect stat.
* **Distance:** Filter by how far away the monster was caught (in kilometers).

---

## 7. Raid Prep & Counters
The **Raid Prep** tab automatically updates from the cloud to show you the current rotation of active boss battles.

1. Tap on any boss in the list.
2. The app will immediately generate the perfect search string to find your best counters against that specific boss.
3. Scroll down to see the **Top 30 Counters** calculated by an independent simulator.
4. You can toggle between **Level 40** and **Level 50** counter lists, as well as **Standard** (no dodging) vs **Dodging** simulation strategies.
