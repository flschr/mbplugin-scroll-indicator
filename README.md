# Scroll Progress Bar for Micro.blog

This Micro.blog plugin adds a simple scroll progress indicator to your blog. It displays a horizontal bar at the top of the screen that fills up as the user scrolls down the page.

## Features

- Customizable bar color
- Adjustable bar height
- Toggle to enable/disable the bar

## Installation

1. Download or clone this repository.
2. Upload the plugin to your Micro.blog account via the Plugins section.
3. Configure the plugin settings:
   - **Enable** the progress bar
   - Choose a **color**
   - Set the **height** (e.g., `4px`, `2px`, etc.)

## Settings (`plugin.json`)

| Setting | Description | Example |
|--------|-------------|---------|
| `enabled` | Enable or disable the scroll progress bar | `true` |
| `color` | Progress bar color in HEX format | `#007aff` |
| `height` | Height of the progress bar | `4px` |

## How it Works

The plugin injects CSS into the `<head>` and JavaScript into the `<footer>` of your Micro.blog theme. As users scroll down the page, the JavaScript calculates the scroll percentage and adjusts the width of the bar in real-time.

## License

MIT