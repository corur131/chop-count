# Chop Count

Calorie, macro and fitness tracker built for Nigerian food.

- **181 foods** in real Nigerian portions: swallows, soups, rice dishes, proteins, street food, fast food, biscuits and drinks. Values from the FAO/INFOODS West Africa Food Composition Table 2019, USDA FoodData Central, Nigerian lab studies and pack labels; recipe-based estimates are marked in the app.
- **Plate builder** with an oil-level setting for soups and stews, saved "usual plates", and your own foods from pack labels.
- **What should I eat?** suggests Nigerian meal combos that fit the calories, protein and naira budget you have left.
- **Measured metabolism:** after two weeks of logging and weigh-ins, targets follow your real daily burn instead of a formula.
- **Home workouts** for gaining, losing or maintaining weight, with animated demonstrations.
- Water, steps, weekly weigh-ins and a daily checklist.

## Get the app

- **Android:** download `chop-count.apk` from the [latest release](https://github.com/corur131/chop-count/releases/latest) and install it. Updates install over the old app and keep your data.
- **iPhone or any browser:** open https://corur131.github.io/chop-count/ and add it to your home screen.

Data stays on your phone. Use **Me → Backup** to copy a backup code.

## How it's built

`web/` is the whole app in one HTML file. Every push to `main` builds a signed Android APK with Capacitor on GitHub Actions, publishes it as a release, and deploys `web/` to GitHub Pages.
