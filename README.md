# Mindful Redirect Page

A powerful, emotionally resonant redirect page designed to help you stay focused and avoid distractions. This page serves as a meaningful intervention when attempting to access blocked websites, helping you reconnect with your goals and maintain productivity.

## Features

### 1. Time Awareness
- Dynamic countdown showing days remaining in the year
- Real-time reminder of time's value and finite nature

### 2. Personal Goal Setting
- Input and storage for your top 3 yearly goals
- Persistent storage using localStorage to maintain your goals between visits

### 3. Visual Motivation
- Split-screen comparison showing the paths of distraction vs. achievement
- Custom imagery to reinforce the consequences of choices
- Requires images:
  - `images/loser.jpg` - Representing distraction
  - `images/success.jpg` - Representing achievement

### 4. Emotional Engagement
- Rotating motivational quotes
- Background audio with toggle control
- Message to future self feature
- Personal reflection journal

### 5. Video Resources
Two carefully selected motivational videos:
- "THE PAIN OF REGRET"
- "The Fear Is Never Reaching Your Potential"

### 6. Local Storage Features
The page saves:
- Your three main goals
- Personal reflection notes
- Message to your future self

## Setup

1. Place the `redirect.html` file in your desired directory
2. Create an `images` folder in the same directory
3. Add required images:
   ```
   your-directory/
   ├── redirect.html
   ├── README.md
   └── images/
       ├── loser.jpg
       └── success.jpg
   ```

## Customization

### Modifying the Focus Destination
Change the "Return to Focus" button destination in the HTML:
```html
<a href="YOUR_PRODUCTIVE_SITE_URL" class="cta-button secondary">Return to Focus</a>
```

### Changing Background Music
Replace the audio source URL in the HTML:
```html
<source src="YOUR_AUDIO_URL" type="audio/mpeg">
```

### Modifying Quotes
Edit the quotes array in the JavaScript section:
```javascript
const quotes = [
    "Your custom quote here",
    // Add more quotes...
];
```

## Browser Compatibility
- Works on all modern browsers (Chrome, Firefox, Safari, Edge)
- Requires JavaScript enabled
- Uses modern CSS features (flexbox, grid, backdrop-filter)

## Privacy
All user data (goals, reflections, messages) is stored locally in the browser's localStorage and is never transmitted to any server.

## License
Feel free to modify and use this code for personal use. Please maintain attribution comments in the source code.
