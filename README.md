# HTML Calculator

A simple calculator built with **HTML**, **CSS**, and a sprinkle of **JavaScript**. Perfect for basic arithmetic in the browser.

## Features
- Add, subtract, multiply, divide
- Clear (C) and delete (⌫)
- Keyboard input support (0–9, +, -, *, /, =, Enter, Backspace)
- Responsive layout for mobile and desktop

## Tech Stack
- **HTML** for structure
- **CSS** for styling
- **JavaScript** for logic

## Getting Started
1. Clone or download the project files.
2. Open `index.html` in any modern web browser.

```bash
# Optionally serve with a simple local server
# Python 3
python -m http.server 8080
# Then visit http://localhost:8080
```

## Usage
1. Click the buttons or use your keyboard to enter numbers and operators.
2. Press `=` or `Enter` to calculate.
3. Use `C` to clear all, or `⌫` to delete the last digit.

## File Structure
```
html-calculator/
├── index.html       # Markup and layout
├── styles.css       # Calculator styles
└── script.js        # Calculation logic & events
```

## Customization
- **Colors & spacing**: edit `styles.css`.
- **Keyboard shortcuts**: modify the key handlers in `script.js`.
- **Buttons/layout**: adjust the grid in `index.html`.

## Accessibility Notes
- Focus states for buttons
- `aria-label` attributes on interactive controls
- Sufficient color contrast recommended (check in `styles.css`)

## Browser Support
Works on latest Chrome, Edge, Firefox, and Safari.

## Troubleshooting
- **Nothing happens on click**: ensure `script.js` is correctly linked in `index.html`.
- **Keyboard not working**: verify the `keydown` listener is attached to `document`.
- **Display shows NaN/Infinity**: handle divide-by-zero or invalid input in `script.js`.

## License
This project is open source. You may use, modify, and distribute it.

---
**Author:** Your Name
**Demo/Screenshot (optional):** Add `screenshot.png` and link it here.

