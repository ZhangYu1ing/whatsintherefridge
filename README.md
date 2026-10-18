# 冰箱里面有什么 (What's in the Fridge)
A mobile-first, single-file web prototype for tracking the food in your fridge and planning tonight's dinner.

## Features
- **Home**: food summary grouped by zone (冷藏 fridge / 冷冻 freezer / 冰箱外 outside) and a dinner preview.
- **Photo intake**: upload a photo and review recognized items (currently a mock, with hard-coded results).
- **My fridge**: drag items between zones, edit name/quantity, or mark as used up.
- **Dinner**: add a dish with ingredients; unknown ingredients are auto-added to the fridge zone.

## Run
Open `index.html` in a browser. No build or dependencies required.

## Status
Prototype. Data lives in memory only and resets on refresh. Photo recognition is simulated.

## Problems
- Add new ingredient not working.

## Limitations
- The date is hard-coded and does not update dynamically.
- Multi-user sharing does not work yet.
- The animations need a better design.

## Next Steps
- Add a database for storing and sharing data.
- Test and verify object detection for photo intake.
- Register recipes from well-known chefs, so users can follow a chef's account and obtain recipes.
- Add secret and surprise recipes that pop up based on a main ingredient in stock.