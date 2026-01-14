# 📦 TrunkPack - Smart 3D Trunk Packing Optimizer

> Pack more, stress less. Visualize and optimize how boxes fit in your trunk with real-time 3D simulation.

A free, browser-based 3D packing optimization tool that helps you maximize trunk space when moving, delivering, or organizing cargo. No installation, no sign-up required—just open and start packing smarter.

## ✨ Key Features

- **Flexible Trunk Spaces**: Model 1-4 different trunk sections with custom dimensions
- **Real-Time 3D Visualization**: Interactive 3D rendering with rotation and zoom controls
- **Custom Box Types**: Define up to 10 different box sizes with custom names
- **Smart Packing Strategies**:
  - Space Priority: Balanced, Front First, or Back First
  - Height Strategy: Minimize Height or Fill Complete
- **Box Rotation**: Optional automatic rotation for optimal packing
- **Manual Quantity Adjustment**: Fine-tune results with +/- buttons
- **Instant Calculations**: Real-time volume utilization and space metrics
- **Unit Support**: Switch between inches, centimeters, and millimeters
- **Local Storage**: Settings saved locally in your browser
- **Fully Responsive**: Works on desktop, tablet, and mobile devices
- **Offline Support**: Works without internet after initial load
- **Material Design 3**: Modern, clean interface with step-by-step guidance

## 🚀 Quick Start

### For Users

1. Open `landing.html` to learn about features, or jump straight to `index.html` to start packing
2. **Step 1**: Model your trunk spaces by entering dimensions (add up to 4 sections)
3. **Step 2**: Set box sizes with custom names and dimensions
4. **Step 3**: Pick a packing strategy that fits your needs
5. **Step 4**: Adjust quantities and visualize in real-time 3D

### For Developers

```bash
# Clone the repository
git clone https://github.com/Dave-Suzuki/packing-helper.git
cd packing-helper

# Open in browser
open index.html

# Or serve with a local server
python -m http.server 8000
# Visit http://localhost:8000
```

## 📖 How It Works

The app uses a sophisticated 3D bin-packing algorithm that:
1. Creates a unified occupation grid for all trunk spaces
2. Sorts boxes by volume (largest first by default)
3. Evaluates placement positions based on your selected strategy
4. Considers box rotations if enabled
5. Optimizes for height and space distribution
6. Allows manual adjustments with automatic re-optimization

### Packing Strategies

**Space Priority:**
- **Balanced**: Even distribution across all spaces
- **Front First**: Fill front sections before moving to back
- **Back First**: Fill back sections before moving to front

**Height Strategy:**
- **Minimize Height**: Keep boxes low across all spaces
- **Fill Complete**: Fill each section completely before moving to next

## GitHub Pages Deployment

This repository is set up to automatically deploy to GitHub Pages using GitHub Actions.

### Initial Setup

1. Push your code to GitHub:
   ```bash
   git add .
   git commit -m "Initial commit: Car Trunk Packing Calculator"
   git push origin main
   ```

2. Enable GitHub Pages in your repository settings:
   - Go to **Settings** → **Pages**
   - Under **Source**, select **GitHub Actions**
   - The workflow will automatically deploy your site

3. Your site will be available at:
   `https://[your-username].github.io/packing-helper/`

### Automatic Deployment

The GitHub Actions workflow (`.github/workflows/deploy.yml`) will automatically:
- Deploy whenever you push to the `main` branch
- Deploy when you manually trigger the workflow
- Update the site within a few minutes of each push

## Local Development

Simply open `index.html` in a web browser. No build process or server required!

## 🛠 Technologies Used

- **HTML5/CSS3**: Modern responsive design with Material Design 3
- **JavaScript (ES6+)**: Core application logic
- **Three.js (r128)**: 3D visualization and rendering
- **Tailwind CSS**: Landing page styling
- **Roboto Font**: Google's Material Design typography
- **LocalStorage**: Browser-based settings persistence
- **Responsive Design**: CSS Grid and Flexbox

## 🎨 Design System

TrunkPack follows Material Design 3 principles:
- **Primary Color**: Teal gradient (#4ecdc4 → #44a08d)
- **Typography**: Roboto font family
- **Elevation**: Subtle shadows and depth
- **Motion**: Smooth transitions and animations
- **Accessibility**: Proper contrast ratios and touch targets

## 📝 Recent Updates

### Latest Version (January 2025)
- ✅ Flexible trunk spaces (1-4 configurable spaces)
- ✅ Dynamic box type management (up to 10 types)
- ✅ Packing optimization preferences (Space Priority + Height Strategy)
- ✅ Material Design 3 styling with custom TrunkPack logo
- ✅ Step-by-step user guidance (numbered 1-4)
- ✅ Fixed visibility issues with dropdowns and text
- ✅ Fixed 3D viewport to stay centered while scrolling
- ✅ Mobile responsive design improvements
- ✅ Professional landing page added

## 🔒 Privacy & Security

- **No tracking**: We don't collect any user data
- **Local storage only**: All data stays on your device
- **No accounts**: No sign-up or authentication required
- **No external servers**: Everything runs in your browser
- **Open source**: Fully transparent codebase

## 🤝 Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

### Development Workflow

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Test thoroughly on desktop and mobile
5. Commit with clear messages
6. Push to your branch
7. Open a Pull Request

## License

MIT License - see LICENSE file for details

---

Made with ❤️ for better packing experiences
