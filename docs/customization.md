# Customization Guide

## Adding New Questions

1. **Add to HTML**: Create new question div with unique ID
2. **Update JavaScript**: Add new question to answers object
3. **Add Event Listeners**: Include new buttons in event listener setup

## Changing Colors

### Primary Theme Colors
```css
/* Main gradient */
background: linear-gradient(135deg, #YOUR-COLOR-1, #YOUR-COLOR-2);

/* Button colors */
.fact-button { background: linear-gradient(135deg, #GREEN-1, #GREEN-2); }
.myth-button { background: linear-gradient(135deg, #RED-1, #RED-2); }
