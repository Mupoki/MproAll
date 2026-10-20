# 💻 mproAll

> A lightweight, modular web desktop environment and PC-software workspace designed for Chromebook and browser environments, featuring Apple's **Liquid Glass** design system.

---

## ✨ Features

* **Apple Liquid Glass UI**: Clean frosted-glass aesthetics, subtle blurs, refined typography, and gorgeous depth inspired by macOS Sonoma and VisionOS.
* **Sleek Setup Wizard (`Index.html`)**: A native-feeling desktop installation popup complete with a smooth setup sequence that boots seamlessly into your workspace.
* **Modular App Workspace (`app.html`)**: Easily add, remove, or modify web apps and tools using a clean JavaScript registry array. 
* **Persistent Customization (`settings.html`)**: Powered by browser `localStorage`, letting you configure dark/light themes, custom welcome titles, and background wallpapers.
* **Zero Bloat**: Pure, dependency-free HTML, CSS, and JavaScript—fast, efficient, and ready to deploy anywhere.

---

## 📁 Project Structure

Make sure all files are saved in the same root folder:

mproAll/
├── Index.html      # The Liquid Glass setup/installer wizard
├── app.html        # The main workspace dashboard & app launcher
└── settings.html   # Persistent system preferences & styling manager


## 🚀 Quick Start / Installation
Clone or download this repository to your local machine or Chromebook environment.

Open Index.html in any modern web browser to run the setup wizard.

Click Start Installation to experience the smooth setup sequence, which will automatically direct you to your workspace.

##🛠️ How to Add or Modify Apps

Open app.html and look for the appsList JavaScript array. You can easily add new apps, change links, or customize icons:

const appsList = [
    {
        name: "Your App Name",
        url: "[https://your-link-here.com](https://your-link-here.com)",
        isExternal: true, // Opens in a new tab
        svg: `<svg>...</svg>` // Custom SVG icon path
    }
];
