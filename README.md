# Interactive Cell Cycle

![Interactive Cell Cycle](https://img.shields.io/badge/HTML5-CSS3-blue?logo=html5)
![GitHub](https://img.shields.io/github/license/<your-username>/<your-repo>?style=flat-square)
![GitHub last commit](https://img.shields.io/github/last-commit/<your-username>/<your-repo>?style=flat-square)

An interactive web-based visualization of the cell cycle, showcasing its phases (G0, G1, S, G2, M, and Interphase) with tooltips providing detailed descriptions. Built with HTML, CSS, and JavaScript, this project uses a background image (`cell_cycle.png`) to guide users, with transparent, circular phase areas that reveal information on hover or click.

[🔗 Live Demo](https://justaidenn.github.io/cell-cycle/)

## Table of Contents
- [Interactive Cell Cycle](#interactive-cell-cycle)
  - [Table of Contents](#table-of-contents)
  - [Features](#features)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Deployment](#deployment)
  - [File Structure](#file-structure)
  - [Contributing](#contributing)
  - [License](#license)
  - [Credits](#credits)

## Features
- **Interactive Phases**: Hover or click on each phase (G0, G1, S, G2, M, Interphase) to display a tooltip with a brief description.
- **Transparent Design**: Phases are invisible circles, relying on the `cell_cycle.png` background for visual context, creating a clean and image-driven experience.
- **Responsive Layout**: Optimized for desktop and mobile, with click support for touch devices.
- **Dynamic Effects**: Smooth hover animations (scale and rotate) enhance user interaction.
- **Custom Tooltip**: G0 Phase has a wider tooltip (300px) for improved readability.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repo>.git
   ```
2. Navigate to the project directory:
   ```bash
   cd <your-repo>
   ```
3. Ensure `cell_cycle.png` is in the same directory as `index.html`.

## Usage
1. Open `index.html` in a browser:
   - Use a local web server for best results (e.g., `python -m http.server 8000`).
   - Access at `http://localhost:8000`.
2. Hover over phase areas to view tooltips with phase descriptions.
3. Click phases on mobile devices to toggle tooltips.
4. The Interphase "Core" label is visible at the center; other phases are transparent, guided by `cell_cycle.png`.

## Deployment
Host the project on GitHub Pages:
1. Push `index.html` and `cell_cycle.png` to your repository.
2. Go to **Settings** > **Pages** in your GitHub repository.
3. Set the source to the `main` branch and `/ (root)` folder.
4. Save, and access your site at `https://<your-username>.github.io/<your-repo>`.

Alternatively, deploy on:
- [Netlify](https://www.netlify.com): Drag and drop files.
- [Vercel](https://vercel.com): Import repository or upload files.
- [Surge](https://surge.sh): Use `npm install -g surge` and `surge`.

## File Structure
```
<your-repo>/
├── index.html          # Main HTML file with CSS and JavaScript
├── cell_cycle.png      # Background image for phase visualization
└── README.md           # Project documentation
```

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/YourFeature`).
3. Commit changes (`git commit -m 'Add YourFeature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a Pull Request.

Please follow the [Code of Conduct](CODE_OF_CONDUCT.md) and report issues via [GitHub Issues](https://github.com/<your-username>/<your-repo>/issues).

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Credits
- **Developed by**: [Aiden Perera](https://github.com/JustAidenn)
- **Background Image**: `cell_cycle.png` (source: unknown)
- **Inspiration**: Educational resources on the cell cycle.
- **Built with**: HTML5, CSS3, JavaScript.

---

⭐ If you find this project useful, please give it a star on [GitHub](https://github.com/JustAidenn/cell-cycle)!