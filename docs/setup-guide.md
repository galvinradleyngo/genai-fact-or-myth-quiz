# Setup Guide

## Canvas LMS Integration

### Method 1: HTML Editor (Recommended)
1. Navigate to your Canvas course
2. Go to Pages → Create new page or edit existing
3. Click the HTML Editor button (`</>`) in the toolbar
4. Copy the complete code from `canvas-integration/embed-code.html`
5. Paste into the HTML editor
6. Save the page

### Method 2: File Upload
1. Upload `index.html` to Canvas Files
2. Link to the file from your course content
3. Students can download and run locally

## Standalone Website

### Option A: GitHub Pages (Free Hosting)
1. In your repository settings
2. Scroll to "Pages" section
3. Select source: "Deploy from a branch"
4. Choose: main branch / root
5. Your quiz will be live at: `https://username.github.io/genai-fact-or-myth-quiz`

### Option B: Local Development
1. Clone the repository
2. Open `index.html` in any web browser
3. No server required!

## Troubleshooting

### Canvas Issues
- **Code not working**: Ensure you copied the complete HTML including `<script>` tags
- **Styling missing**: Canvas might strip some CSS - this is normal with the embedded version
- **Not responsive**: Check Canvas theme settings

### Browser Issues
- **JavaScript disabled**: Enable JavaScript in browser settings
- **Old browser**: Requires modern browser (Chrome 60+, Firefox 55+, Safari 12+)
