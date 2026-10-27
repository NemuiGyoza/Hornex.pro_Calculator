# Hornex Crafting Calculator

A visual crafting simulator and budget analysis tool built for **Hornex.pro**. This utility calculates your statistical odds, expected costs, and potential success rates when crafting high-tier petals based on a custom petal budget.

## Live Demo
Check out the live, interactive app here: [Hornex.pro Calculator](https://github.io)

## Features

* **Supported Recipes:**
  * Ultra → Super (1.00% Success Chance)
  * Super → Hyper (0.51% Success Chance)
* **Custom Budgeting:** Input any petal budget up to 5,000 petals to simulate your crafting session.
* **Deep Statistical Analysis:**
  * **Craft Chance:** Displays base recipe success rates.
  * **Average Loss on Fail:** Accounts for variable petal recovery mechanics.
  * **Expected Cost per Success:** Calculates the average petal investment required per successful craft.
  * **Expected Rolls:** Determines how many total attempts your budget realistically yields.
  * **Success Chance:** Computes the mathematical probability of getting at least one success from your budget.
  * **Most Likely Result:** Pinpoints the exact number of successful crafts you are statistically most prone to land on.
* **Interactive Probability Chart:** Visualizes a percentage breakdown for every possible success outcome (0, 1, 2, or more successes) using responsive scale bars.

## How it Works

The calculator uses exact probability logic based on the internal game rules:
1. **Attempt Cost:** Each crafting roll attempts to consume 5 petals.
2. **Partial Recovery on Failure:** On a failed attempt, the game randomly returns a portion of your petals. The calculator simulates an equal 25% probability distribution for losing either 1, 2, 3, or 4 petals on failure (averaging a loss of 2.5 petals per fail).
3. **Success Cost:** A successful craft uses the full 5 petals without a recovery return.

## Technologies Used

* HTML5
* CSS3 / Modern UI Styling
* JavaScript (ES6)

## Guild Recruitment & Contact
I am the leader of the guild **Yippy [Yipp]**! If you are interested in joining our community, or if you have questions and feedback regarding this calculator, feel free to reach out directly.

* **Discord:** `@nemui_gyoza` (DM me directly to apply!)

### Guild Requirements:
* **Strict Rule Compliance:** You must strictly follow all server rules.
* **Represent the Tag:** Rules apply both inside the Discord server and outside of it. As long as you are wearing the **[Yipp]** tag, you are expected to follow them everywhere.

## Feedback & Contributions
This project is an ongoing work in progress! If you encounter any bugs, have suggestions for new features, or want to contribute more recipe formulas:
1. Open an issue on this repository.
2. Submit a pull request with your code updates.
