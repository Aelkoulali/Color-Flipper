# 🗂️ Color Flipper 🟥🔄🟪🔄🟦🔄🟩
he Color Flipper is a simple web project built with HTML, CSS, and JavaScript. It randomly changes the page’s background color whenever you click a button. The project uses an array of colors, selects a random one using `Math.random()` and `Math.floor()`, and applies it through `document.body.style.backgroundColor`, while handling user interaction using `addEventListener()` and grabbing elements with `getElementById() / querySelector()`.

## ✅ Key Features
- Randomly changes the page background color with each click (Color Flipper effect).
- Stores available colors in an array and picks one automatically.
- Uses Math.random() to generate a random index and Math.floor() to convert it into a valid array position.
- Uses the array’s size with array.length to ensure the random index is always in range.
- Updates styling instantly using document.body.style.backgroundColor.
- Button/interaction handling with addEventListener().
- Accesses elements using document.getElementById() and document.querySelector().

## 🛠️ Tech Stack
- HTML
- CSS
- JavaScript :
   - arrays + random selection (Math.random, Math.floor)
   -  DOM element targeting (getElementById, querySelector)
   -  event control (addEventListener)
   -  background update (document.body.style.backgroundColor)
 

## ▶️ How to Run
1. Open `index.html` in your browser.
