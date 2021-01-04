## Challenge: add more sections

--- challenge ---

Add more sections to your recipe using parallax scrolling.

--- hints ---
--- hint ---
Some ideas for what you could add are sections on ingredients, preparation, or cooking instructions.
--- /hint ---
--- hint ---
Remember that you already have sections on your web page that are using parallax scrolling, so think about how many new CSS rule-sets you need.
--- /hint ---
--- hint ---
You can re-use CSS rule-sets for multiple selectors. Add your new sections to the selector list of the rule-set containing `background-attachment: fixed;`.

Then, add new rule-sets to include a background image in your new sections.
```css
.cd-logo, .kitchen-equipment, .cake-ingredients {
  position: relative;
  background-position: center;
  background-attachment: fixed;
  background-repeat: no-repeat;
  background-color: #642580;
  background-size: cover;
  min-height: 50%;
}

.cd-logo {
  background-image: url("CoderDojo.png");
  min-height: 100%;
  background-size: auto;
}

.kitchen-equipment {
  background-image: url("utensils.JPG");
}

.cake-ingredients {
  background-image: url("ingredients.JPG");
}
```
--- /hint ---
--- /hints ---

--- /challenge ---
