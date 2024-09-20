# Spinning 3D Donut

![Spinning 3D Donut](https://github.com/speedyfriend433/spinning-donut/blob/main/demo.gif?raw=true)

A visually appealing spinning 3D donut (torus) built with [Three.js](https://threejs.org/) and deployed on [GitHub Pages](https://pages.github.com/). This project demonstrates basic 3D graphics rendering on the web and serves as a fun introduction to WebGL and Three.js.

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Demo

Check out the live demo of the spinning 3D donut deployed on GitHub Pages:

[https://speedyfriend433.github.io/spinning-3D-donut/](https://speedyfriend433.github.io/spinning-3D-donut/)

## Features

- **3D Rendering:** Utilizes Three.js to create and render a 3D torus.
- **Smooth Animation:** The donut spins continuously, showcasing dynamic rendering.
- **Responsive Design:** Adapts to different screen sizes and devices.
- **Interactive Lighting:** Ambient and point lights enhance the visual appeal.
- **Optimized Performance:** Efficient rendering for smooth animations.

## Technologies Used

- [HTML5](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [Three.js](https://threejs.org/)
- [GitHub Pages](https://pages.github.com/)

## Getting Started

Follow these instructions to set up the project locally on your machine.

### Prerequisites

- **Git:** Ensure you have Git installed. If not, download it from [here](https://git-scm.com/downloads).
- **Web Browser:** A modern web browser like Chrome, Firefox, or Edge.

### Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/speedyfriend433/spinning-donut.git
   ```

2. **Navigate to the Project Directory:**

   ```bash
   cd spinning-donut
   ```

3. **Open `index.html` in Your Browser:**

   - You can open the file directly:
     - Locate the `index.html` file in the project directory.
     - Double-click to open it in your default browser.
   - **Or** use a local development server for a better experience:
     - If you have [Node.js](https://nodejs.org/) installed, you can use `http-server`:
       ```bash
       npm install -g http-server
       http-server
       ```
     - Open the provided local URL in your browser.

## Usage

Once you've opened the project locally or accessed the live demo, you'll see a 3D donut spinning in the center of the screen. The animation runs automatically and adapts to your browser window size.

## Customization

Feel free to customize the spinning donut to your liking. Here are some ideas:

- **Change Colors:**
  Modify the `MeshStandardMaterial` color in `index.html` to alter the donut's color.
  ```javascript
  const material = new THREE.MeshStandardMaterial({ color: 0xff6347, wireframe: false });
  ```
  
- **Adjust Rotation Speed:**
  Tweak the rotation increments in the animation loop.
  ```javascript
  torus.rotation.x += 0.01;
  torus.rotation.y += 0.01;
  ```
  
- **Add Textures:**
  Apply textures to the donut for a more detailed appearance.

- **Interactive Controls:**
  Incorporate mouse or touch interactions to allow users to control the donut's rotation.

## Deployment

This project is deployed using GitHub Pages. To deploy your own version:

1. **Push Your Changes to GitHub:**

   ```bash
   git add .
   git commit -m "Your commit message"
   git push origin main
   ```

2. **Enable GitHub Pages:**
   - Navigate to your repository on GitHub.
   - Click on **Settings**.
   - Scroll down to the **Pages** section.
   - Under **Source**, select the branch (`main`) and folder (`/root`) to deploy.
   - Click **Save**.
   
3. **Access Your Deployed Site:**
   - Your site will be available at `https://speedyfriend433.github.io/spinning-donut/` within a few minutes.

## Contributing

Contributions are welcome! If you'd like to enhance this project, please follow these steps:

1. **Fork the Repository**
2. **Create a Feature Branch:**

   ```bash
   git checkout -b feature/YourFeature
   ```

3. **Commit Your Changes:**

   ```bash
   git commit -m "Add your feature"
   ```

4. **Push to the Branch:**

   ```bash
   git push origin feature/YourFeature
   ```

5. **Open a Pull Request**

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- [Three.js](https://threejs.org/) for the powerful 3D library.
- [GitHub Pages](https://pages.github.com/) for easy deployment.
- Inspiration from various web development tutorials and resources.
