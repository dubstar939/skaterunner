# Third Coast Shread by 939PRO Studios

An awesome skateboarding browser game built with HTML5 Canvas and JavaScript.

## 🎮 How to Play

- **SPACE / UP Arrow / Tap**: Jump (hold for higher jump)
- **DOWN Arrow / Swipe Down**: Perform tricks
- **Collect Stars**: Bonus points!
- **Avoid Obstacles**: Don't crash!

## 🚀 Deploy to Vercel

### Option 1: Vercel CLI

```bash
# Install Vercel CLI
npm install -g vercel

# Deploy
vercel

# Production deployment
vercel --prod
```

### Option 2: GitHub Integration

1. Push this repository to GitHub
2. Go to [vercel.com](https://vercel.com)
3. Click "New Project"
4. Import your GitHub repository
5. Click "Deploy"

### Option 3: Drag & Drop

1. Go to [vercel.com/new](https://vercel.com/new)
2. Drag and drop your project folder

## 📁 Project Structure

```
/workspace
├── index.html          # Main game file (HTML + CSS + JS)
├── sprite_sheet.png    # Character sprite sheet
├── vercel.json         # Vercel configuration
├── .gitignore          # Git ignore rules
└── README.md           # This file
```

## 🛠️ Local Development

Simply open `index.html` in a modern web browser, or use a local server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (npx)
npx serve

# Using PHP
php -S localhost:8000
```

Then navigate to `http://localhost:8000`

## 🎨 Features

- Smooth sprite-based character animation
- Multiple levels with increasing difficulty
- Trick system with combo bonuses
- Particle effects and screen shake
- Responsive design for mobile and desktop
- Touch controls for mobile devices
- Hold-to-charge jump mechanic
- High score persistence using localStorage
- Procedural sound effects using Web Audio API

## 📱 Mobile Support

The game is fully responsive and supports touch controls:
- Tap to jump
- Swipe down to perform tricks
- Long press and release for charged jumps

## 🔧 Configuration

Edit `vercel.json` to customize:
- Security headers
- Cache control
- URL rewrites

## 📄 License

© 939PRO Studios. All rights reserved.
