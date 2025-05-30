# Bridal Shower Invitation - Kelsey Ronn

A beautiful, private bridal shower invitation website featuring sunflowers and burgundy roses.

## 🌻 Features

- **Private Access**: Only accessible with a secret invite token
- **Beautiful Design**: Sunflower and burgundy rose theme with elegant typography
- **Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Complete Event Details**: Date, time, location, and RSVP information

## 📅 Event Details

- **Bride**: Kelsey Ronn
- **Date**: Saturday, June 22, 2025
- **Time**: 1-3pm
- **Location**: 610 Forsyth Crescent
- **RSVP**: Karen Ronn - 306-221-9518

## 🖥️ How to View Locally

### Method 1: Open Directly in Browser (Easiest)

1. **Open the file directly:**
   ```bash
   open index.html
   ```
   Or simply double-click the `index.html` file in Finder

2. **Add the secret token to see the full invitation:**
   - In your browser's address bar, add `?invite=kelsey-shower-2025` to the end of the URL
   - Full URL should look like:
     ```
     file:///path/to/your/bridalshower/index.html?invite=kelsey-shower-2025
     ```

### Method 2: Using a Local Web Server

1. **Start a local server:**
   ```bash
   python3 -m http.server 8000
   ```

2. **Open in browser:**
   - Go to: `http://localhost:8000`
   - Add the token: `http://localhost:8000?invite=kelsey-shower-2025`

3. **Stop the server when done:**
   - Press `Ctrl+C` in the terminal

## 🔒 Privacy & Access

- **Without token**: Visitors see a "Private Invitation" message
- **With token**: Full invitation is displayed
- **Secret token**: `kelsey-shower-2025`

To change the secret token, edit line 282 in `index.html`:
```javascript
const SECRET_TOKEN = 'your-new-token-here';
```

## 🌐 Deployed Version

The invitation is also available online at:
```
https://jonathanronn.github.io/bridalshower/?invite=kelsey-shower-2025
```

## 🎨 Design Theme

- **Colors**: Warm yellows, oranges, and deep burgundy
- **Fonts**: Dancing Script (decorative) + Cormorant Garamond (body)
- **Decorations**: Sunflowers (🌻), burgundy roses (🌹), and sun (☀️) emojis
- **Style**: Modern with glass-morphism effects and elegant gradients

## 📱 Mobile Friendly

The invitation automatically adjusts for different screen sizes:
- Desktop: Full-size elegant layout
- Tablet: Optimized spacing and font sizes
- Mobile: Compact, touch-friendly design

---

*Created with love for Kelsey's special day* 💕