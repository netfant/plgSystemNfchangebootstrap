# Bootstrap 4 Override Plugin for Joomla 3.x

A system plugin for the Joomla CMS that programmatically replaces the core Bootstrap 2 assets with Bootstrap 4, enabling the use of modern frontend tools.

---

### Project Context & Purpose

This plugin was developed for the Joomla 3.x platform to solve a common developer pain point: the core system shipped with an outdated version of Bootstrap (v2). This created challenges for developers wanting to use modern frontend design patterns.

While Joomla 3.x is now a legacy platform, this project serves as a technical example demonstrating:

* **Deep Integration with a Major CMS:** The ability to work within the Joomla framework and its specific plugin architecture.
* **Effective Problem Solving:** Engineering a targeted solution to a real-world developer obstacle.
* **Professional PHP Development:** A clear example of structured PHP code within a larger application.

### Core Functionality

This plugin modifies the document's asset includes. It does **not** automatically convert class names in your template or overrides.

* **Bootstrap 2 Removal:**
    * Removes the core Bootstrap 2 CSS files.
    * Removes the core Bootstrap 2 JS files.
* **Bootstrap 4 Integration:**
    * Adds the Bootstrap 4 CSS file.
    * Adds the Bootstrap 4 JS files (including Popper.js).

### Installation

1.  Download the latest release as a `.zip` file.
2.  Install via the standard Joomla extension manager.
3.  Enable the plugin from the plugin manager.

### Contribution

Bug reports, suggestions, and pull requests are welcome. Please feel free to open an issue on this repository.
