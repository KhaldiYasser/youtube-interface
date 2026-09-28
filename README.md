# YouTube Homepage Clone 🎥

A responsive YouTube homepage clone built strictly with **HTML5** and **CSS3**. This project focuses on building a responsive grid layout, utilizing Flexbox, and implementing advanced styling techniques for fixed and interactive elements.

---

## 🌟 Features

* **Fixed Header:** Includes the logo, search bar with tooltips, creation & notification buttons, and user profile image.
* **Fixed Navigation Sidebar:** Contains main navigation links (Home, Explore, Subscriptions, etc.).
* **Responsive Video Grid:**
  * Automatically adapts to mobile, tablet, and desktop screens using `CSS Grid` and `@media queries`.
  * Displays video thumbnails, duration badges, channel avatars, video titles, channel names, views, and upload dates.
* **Interactive Tooltips & Hover Effects:** Displays informational tooltips on hover over toolbar icons.
* **Google Fonts Integration:** Utilizes the `Roboto` font to match YouTube's official design language.

---

## 📁 Project Structure

```text
.
├── index.html              # Main HTML document
├── styles/
│   ├── general.css         # Global styles and font declarations
│   ├── header.css          # Top navigation bar styling
│   ├── navbar.css          # Left sidebar navigation styling
│   └── video.css           # Video grid layout and responsive breakpoints
└── images/
    ├── iconts/             # UI SVG icons and user avatar
    ├── channel-picture/    # Channel avatar images
    └── video-picture/      # Video thumbnail images