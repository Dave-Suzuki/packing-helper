# Car Trunk Box Packing Calculator

A web-based 3D packing calculator that helps you optimize how to pack boxes into your car trunk. The calculator supports L-shaped trunk spaces with different heights in the front and back sections.

## Features

- **3D Visualization**: Interactive 3D view of your trunk and packed boxes using Three.js
- **L-Shaped Trunk Support**: Handles trunks with different heights in front and back sections
- **Box Rotation**: Option to allow boxes to be rotated for optimal packing
- **Multiple Box Types**: Configure up to 3 different box types with custom dimensions
- **Real-time Calculation**: Automatically calculates optimal packing arrangement
- **Quantity Adjustment**: Manually add or remove boxes after initial calculation
- **Unit Support**: Switch between inches, centimeters, and millimeters
- **Local Storage**: Settings are saved locally in your browser
- **Responsive Design**: Works on desktop, tablet, and mobile devices

## How to Use

1. Enter your trunk dimensions:
   - **Back Zone**: The taller section at the back of the trunk
   - **Front Zone**: The shorter section at the front of the trunk
   - Both zones are automatically centered when widths differ

2. Configure your box types:
   - Enable/disable each box type
   - Set dimensions (Width × Height × Depth)
   - Customize box names

3. Click "Calculate Optimal Fit" to see the best packing arrangement

4. Use the quantity controls to manually add or remove boxes

5. Rotate the 3D view by dragging, and zoom with your mouse wheel or pinch gesture

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

## Technologies Used

- **HTML5/CSS3**: Modern responsive design
- **JavaScript**: Core application logic
- **Three.js**: 3D visualization and rendering
- **LocalStorage**: Browser-based settings persistence

## License

MIT License - see LICENSE file for details
