# Calculator

A simple calculator built with **HTML**, **CSS**, Perfect for basic arithmetic in the browser.

## Features
- Add, subtract, multiply, divide
- Clear (C) and delete (⌫)
- Keyboard input support (0–9, +, -, *, /, =, Enter, Backspace)
- Responsive layout for mobile and desktop

## Tech Stack
- **HTML** for structure
- **CSS** for styling

## Usage
1. Click the buttons or use your keyboard to enter numbers and operators.
2. Press `=` or `Enter` to calculate.
3. Use `C` to clear all, or `⌫` to delete the last digit.

## File Structure
```
html-calculator/
├── index.html       # Markup and layout
├── styles.css       # Calculator styles
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

