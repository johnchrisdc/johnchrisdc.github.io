# JCDC Portfolio (johnchrisdc.github.io)

Personal portfolio website and asset hosting for John Chris Dela Cruz (JCDC), an Android Developer.

## Project Overview

This is a static website hosted on GitHub Pages. It serves as a professional portfolio, hosting various project links, privacy policies for mobile applications, and other static assets.

### Technologies
- **HTML5 / CSS3**
- **Bootstrap 4.3.1**: Used for grid layout and responsive design.
- **Material Design Lite (MDL)**: Used for Material Design components and styling.
- **Google Maps JavaScript API**: Used in the `old_map` section for a ground overlay experiment.
- **Google Fonts**: Material Icons integration.

## Directory Structure

- `/`: Root directory containing the main portfolio (`index.html`) and portfolio PDF.
- `/app`: Contains hosted Android APK files (e.g., `app-potatoinc-release.apk`).
- `/old_map`: A legacy/experimental page featuring a Google Maps ground overlay.
- `/privacy_policy`: HTML files for the privacy policies of various Android apps (e.g., PH Consti, Road Signs).
- `/res`: Static resources including images, icons, and logos used across the site.

## Key Files

- `index.html`: The main landing page of the portfolio, showcasing projects like Waispend, BikeChecks.ph, and RapidPass.ph.
- `portfolio.pdf`: A downloadable version of the developer's resume/portfolio.
- `privacy_policy/*.html`: Standard privacy policy templates for Play Store compliance.

## Usage

This project is intended to be served as a static site. No build process is required. Changes to the HTML or CSS can be made directly and pushed to the repository for deployment via GitHub Pages.

### Adding a Privacy Policy
To add a new privacy policy for an app:
1. Create a new `.html` file in the `privacy_policy/` directory.
2. Link to it from the Play Store Console.

### Updating Portfolio
Modify `index.html` to add or remove project cards. Images should be placed in the `res/` directory.
