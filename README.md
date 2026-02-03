# Valentine's Day Interactive Website 💕

A fun, interactive Valentine's Day website where the "No" button runs away from the cursor!

## Features

- **6 Beautiful Themes**: Pink Blush, Blue Ocean, Purple Dream, Red Romance, Green Nature, and Golden Sunset
- **Personalized Names**: Customize with any name via URL parameters
- **Interactive "No" Button**: The "No" button moves away when you try to hover over it
- **Celebration Page**: Animated confetti when "Yes" is clicked
- **Setup Page**: Easy-to-use interface to generate custom links
- **Responsive Design**: Works on all devices

## How to Use

### Option 1: Use the Setup Page (Easiest!)
1. Go to `setup.html` (or `https://reosoul.github.io/Valentines/setup.html`)
2. Enter the person's name
3. Choose your favorite theme
4. Click "Generate Link" and copy the URL
5. Share the link with your Valentine!

### Option 2: Manual URL Parameters
Add parameters to the URL to customize:
- `?name=YourName` - Change the name
- `&theme=pink` - Choose a theme (pink, blue, purple, red, green, gold)

Example: `https://reosoul.github.io/Valentines/?name=Sarah&theme=blue`

## Available Themes

1. **Pink Blush** (default) - Classic romantic pink
2. **Blue Ocean** - Calm and cool blue tones
3. **Purple Dream** - Dreamy purple gradients
4. **Red Romance** - Bold romantic red
5. **Green Nature** - Fresh and natural green
6. **Golden Sunset** - Warm golden tones

## Hosting on GitHub Pages

1. Create a new repository on GitHub
2. Upload these files to your repository:
   - `index.html`
   - `yes.html`
   - `setup.html`
   - `README.md`

3. Enable GitHub Pages:
   - Go to your repository settings
   - Scroll down to "Pages" section
   - Under "Source", select "main" branch
   - Click "Save"

4. Your site will be available at: `https://yourusername.github.io/repository-name/`

5. Update the base URL in `setup.html`:
   - Open `setup.html`
   - Find the line: `const baseUrl = 'https://reosoul.github.io/Valentines/';`
   - Replace with your GitHub Pages URL

## Files

- `index.html` - Main page with the question and interactive buttons
- `yes.html` - Success/celebration page shown when "Yes" is clicked
- `setup.html` - Setup page to generate custom Valentine's links
- `README.md` - This file

## Credits

Created as a fun Valentine's Day project with love! 💝

