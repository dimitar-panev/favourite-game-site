# Forza Horizon 5 Fan Website - Coursework Project

This document outlines the file structure and provides context for a website dedicated to the game Forza Horizon 5, created as part of university coursework.

## File Structure
.
├── .codebuddy/
├── .idea/
├── .vscode/
├── css/
├── history page/
├── img/
├── js/
├── .editorconfig
├── .gitattributes
├── .gitignore
├── 404.html
├── LICENSE.txt
├── README.md
├── about.html
├── favicon.ico
├── gallery.html
├── history.html
├── package-lock.json
├── package.json
├── site.webmanifest
├── to add.txt
├── webpack.common.js
├── webpack.config.dev.js
├── webpack.config.prod.js
└── why.html

### Directories:

* **.codebuddy/:** Likely contains configuration files for the CodeBuddy editor or related tools.
* **.idea/:** Contains IntelliJ IDEA project-specific configuration files.
* **.vscode/:** Contains Visual Studio Code project-specific configuration files.
* **css/:** Stores CSS stylesheets (`style.css`, `hstyle.css`).
* **history page/:** Contains HTML files for the history of each Forza Horizon game (`fh1.html`, `fh2.html`, `fh3.html`, `fh4.html`, `fh5.html`).
* **img/:** Stores image assets used on the website.
* **js/:** Stores JavaScript files (`script.js`).

### Files:

* **.editorconfig:** Defines coding style conventions for the project.
* **.gitattributes:** Specifies how Git should handle line endings and whitespace.
* **.gitignore:** Specifies intentionally untracked files that Git should ignore.
* **404.html:** The custom "Page Not Found" error page.
* **LICENSE.txt:** Contains the licensing information for the project.
* **README.md:** The main README file for the project, providing general information.
* **about.html:** An HTML page providing information "About" the website or the creator's passion for Forza Horizon.
* **favicon.ico:** The website's icon that appears in browser tabs.
* **gallery.html:** An HTML page showcasing a gallery of Forza Horizon 5 images.
* **history.html:** An HTML page providing a brief history of the Forza Horizon series.
* **package-lock.json:** Records the exact versions of dependencies used in the project (for Node.js projects).
* **package.json:** Contains metadata about the project and lists its dependencies (for Node.js projects).
* **site.webmanifest:** Provides metadata about the web application for Progressive Web App (PWA) features.
* **to add.txt:** Likely a simple text file listing items or features to be added to the website.
* **webpack.common.js:** Common configuration for the Webpack module bundler.
* **webpack.config.dev.js:** Webpack configuration for development builds.
* **webpack.config.prod.js:** Webpack configuration for production builds.
* **why.html:** An HTML page explaining "Why" the creator chose Forza Horizon 5 as their favorite game.
## Project Details
This website is dedicated to the Forza Horizon 5 video game and is part of my university coursework.

### Key Content:

* **Homepage (`index.html`):**
    * **Title:** "Forza Horizon 5 - fav game"
    * **Navigation:** A navbar with links to "About", "History" (with a dropdown for each Forza Horizon game), "Gallery", and "Why".
    * **Main Content:** An article titled "All Forza Games" providing a brief overview of the Forza series (both Motorsport and Horizon) and stating the focus will be on the Horizon series.
    * **Image Gallery:** A container displaying multiple images from the Forza Horizon series (`fhmain1.webp`, `fhmain2.jpg`, etc.).
* **History Page (`history.html`):**
    * **Title:** "History"
    * **Navigation:** Same navbar as the homepage.
    * **Content:** A brief history of the Forza Horizon series, mentioning its Xbox exclusivity and availability on Game Pass. It also encourages users to visit specific game pages in the dropdown menu for more information.
* **Gallery Page (`gallery.html`):**
    * **Title:** "Gallery"
    * **Navigation:** Same navbar as the homepage.
    * **Content:** Currently empty (`<body> <script src="script.js"></script> ... </article>`). It is intended to display a collection of images related to Forza Horizon 5.
* **Why Page (`why.html` - based on commit):**
    * **Title:** Likely "Why"
    * **Content:** Explains the personal reasons why the creator chose the Forza Horizon series as their favorite game, detailing their history with car games, their experience with Forza Horizon 4, and their enjoyment of Forza Horizon 5.
* **About Page (`about.html` - based on commit):**
    * **Title:** Likely "About"
    * **Content:** Probably contains information about the creator of the website and their passion for Forza Horizon 5.

### Technologies Used:

* HTML5
* CSS (`css/style.css`, `css/hstyle.css`)
* JavaScript (`script.js`, potentially jQuery)
* Web Manifest (`site.webmanifest`)


