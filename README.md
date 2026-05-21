# 🌑 NothingSystems - Interactive Sticky Navigation

A sleek, minimalist landing page featuring a high-performance **interactive sticky navigation bar**. Inspired by "Nothing" design aesthetics, this project showcases seamless transitions between a transparent hero state and a focused, functional scrolled state.

## 📱 Live Features

* **Dynamic Scroll Logic:** The navigation bar intelligently detects vertical scroll position to toggle between a transparent "Hero" mode and a solid, elevated "Active" mode.
* **Smooth Navigation:** Utilizes native CSS `scroll-behavior` for elegant, fluid transitions when jumping between site sections.
* **Hover Interactivity:** Modern link underlining and card-lifting effects ($5\text{px}$ translateY) provide immediate tactile feedback.
* **Responsive Grid:** A flexible services layout that automatically adapts to varying screen widths using CSS Grid.

## 🛠️ Technical Stack

* **HTML5:** Semantic structure for optimal SEO and accessibility.
* **CSS3:** Custom layouts using **Flexbox** and **CSS Grid**, plus custom transitions for the navigation lifecycle.
* **Vanilla JavaScript:** Lightweight event listeners to manage scroll-state classes without the need for heavy libraries.

## 🏗️ Project Structure

The project follows a modular, single-file architecture for ease of deployment:

```text
├── nav.html           # Core HTML structure, CSS styles, and JS logic
└── README.md          # Documentation
