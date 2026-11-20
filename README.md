# Firefly Button

An interactive glowing **Firefly Button** built with HTML, CSS (including Tailwind CSS), and JavaScript (powered by Kinet.js for smooth cursor-following motion). Hovering over the button triggers glowing layers and animated firefly particles.

## Features

- **Glowing Hover Effect**: Smooth inner and outer yellow glow layers (`box-shadow` with `mix-blend-mode: screen`) on hover.
- **Animated Firefly Dots**: Seven independent firefly particles that move into position and animate with hovering and dimming keyframes when hovered.
- **Tailwind CSS Utility Styling**: Uses Tailwind CSS via CDN for rapid layout and button styling.

## Project Structure

```text
firefly-button/
├── index.html   # Main markup and CDN dependencies
├── style.css    # Firefly particle animations, glow effects, and layout styles
├── script.js    # Kinet physics setup and mousemove animation handler
└── README.md    # Project documentation