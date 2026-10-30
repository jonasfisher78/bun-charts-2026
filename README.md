# bun-charts v2026 - interactive chart components 2026

> **Zero-dependency animated chart components for the web that transform repository-style data into interactive SVG visualizations, shipping in the current 2026 release.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/jonasfisher78/bun-charts-2026?style=flat-square)](https://github.com/jonasfisher78/bun-charts-2026)

---

<p align="center">
  <a href="https://jonasfisher78.github.io/bun-charts-2026/">
    <img src="https://img.shields.io/badge/Download-bun-charts%20Latest-brightgreen?style=for-the-badge" alt="Download bun-charts">
  </a>
</p>

> **[Download - bun-charts v2026](https://jonasfisher78.github.io/bun-charts-2026/)**

---

[Download Latest Build](https://jonasfisher78.github.io/bun-charts-2026/)

---

## About bun-charts

bun-charts packages a set of interactive chart components for the web, aimed at animated storytelling and data visualization work. Everything renders as SVG, so the results slot neatly into dashboards, blog posts, or product pages where both motion and readability count.

JSON drives each component, and a small amount of browser-side logic starts the animation automatically once a chart scrolls into view. Developers who want ready-made visualization blocks therefore get reusable pieces without extra dependencies or hand-rolled animation code.

---

## Features

- SVG chart components that respond to user interaction in the browser
- Commit heatmap replay for showing repository activity over time
- Adversarial review animation for side-by-side data comparison
- CI race timeline for narrating builds and pipelines
- Workflow split view for branching or parallel processes
- Number counter animation to draw attention to changing values
- Intersection Observer autoplay that kicks off motion on view
- Data-driven embedded JSON for straightforward content injection
- Zero-dependency architecture that keeps integration simple

---

## Installation

Download or clone the repository, then either open the HTML entry file directly in a browser or serve it through any static web host.

```bash
git clone https://github.com/jonasfisher78/bun-charts-2026.git
cd REPO
```

To preview locally, run whichever static server you prefer and load the page in your browser.

---

## Usage

1. Pick the visualization you want to show.
2. Replace the embedded JSON payload with your own data.
3. Adapt the HTML and Tailwind CSS layout so it fits your page.
4. Open the page and let the charts animate as they come into view.

A typical workflow looks like this:

- Place chart data inside the embedded JSON block
- Leave the SVG structure as-is
- Fine-tune animation timing in JavaScript when necessary
- Drop the component into a dashboard or article layout

---

## Configuration

Customization mostly happens right in the HTML and inline data. The usual settings live in the embedded JSON block and the JavaScript hooks around it.

```json
{
  "autoplay": true,
  "chart": "commit-heatmap",
  "animation": "intersection-observer",
  "renderMode": "svg"
}
```

When adapting the components, take a look at the HTML structure, the Tailwind utility classes, and any data attributes connected to the animation flow.

---

## Requirements

- A modern web browser
- Support for HTML, JavaScript, and SVG
- A static file server for local development, if you want one
- Tailwind CSS for the intended layout styling
- No runtime dependencies required

---

## FAQ

**How do I change what the charts display?**  
Edit the embedded data and reload the page. Each chart reflects the JSON input you provide.

**Is it suitable for a dashboard?**  
Yes. The components target web pages, dashboards, and other browser-based layouts.

**What if the animations never start?**  
Make sure the target element is actually visible in the viewport and that the intersection observer logic is running.

**Where can I follow updates?**  
Check the repository history and the project release pages for the newest changes and version details.

**How do I customize the styling?**  
Adjust the Tailwind CSS classes and the surrounding HTML structure until it matches your design.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
