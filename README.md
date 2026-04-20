# 🌊 Tidal-HiFi: Stars UI
<img width="2559" height="1348" alt="screenshot" src="https://github.com/user-attachments/assets/f6bd8bff-79db-42d0-b31c-bc89a27492fd" />
<br>
A custom CSS theme for the Tidal-HiFi Electron wrapper. This theme replaces the heavy, solid dark menus with a modern frosted glass aesthetic, allowing the background to shine through while maintaining a premium feel.

## ✨ Key Features

*   **💎 Unified Glass Base**: High-precision `25px` backdrop blur applied to Search, Profile, and Context menus.
*   **🔍 Perfected Search Bar**: A custom-engineered search input featuring a subtle white tint (`0.05` opacity) and refined 20px pill borders.
*   **🚫 "Black Box" Killer**: Uses recursive transparency rules and variable-nuking to strip away Tidal's stubborn internal dark layers.
*   **🖱️ Responsive Hover**: Smooth, low-latency highlights on all interactable menu items for a tactile navigation experience.
*   **🛠️ Sub-Menu Recovery**: Advanced z-index and positioning logic to ensure "fly-out" menus (Help, Legal, etc.) remain visible and frosted.

## 🚀 Installation

1. Locate your `tidal-hifi` configuration directory:
   - **Linux**: `~/.config/tidal-hifi/`
   - **Windows**: `%APPDATA%/tidal-hifi/`
2. Open your `stars.css` file (or the injection field in the app settings).
3. Paste the provided CSS code.
4. Restart **Tidal-HiFi** to apply the changes.

## 🛠️ Design Specifications


| Component | Style Property | Value |
| :--- | :--- | :--- |
| **Blur Intensity** | `backdrop-filter` | `blur(25px)` |
| **Glass Color** | `background-color` | `rgba(0, 0, 0, 0.4)` |
| **Borders** | `border` | `1px solid rgba(255, 255, 255, 0.1)` |
| **Shadows** | `box-shadow` | `0 10px 40px rgba(0, 0, 0, 0.6)` |

## 🧪 Technical Note

This theme utilizes **wildcard attribute selectors** and **CSS variable overrides** (specifically targeting `--un-bg-opacity`) to bypass the limitations of Tidal's modern web-component structure.

## 👥 Credits

*   **Main Design & Implementation**: [Yoss.dev](https://yoss.dev)

*   **AI Collaborator**: Google Gemini

---

*Maintained by a fellow audiophile. Enjoy the stars!* 🌟

