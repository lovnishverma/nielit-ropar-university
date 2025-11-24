# NIELIT Ropar University Website

This repository contains the source code for the NIELIT Ropar University web portal. It is a web-based project designed to provide comprehensive information regarding the university's academic programs, faculty, and administrative details.

Visit Website: nielit.ac.in

## Overview

The project serves as an informational hub for students and faculty, featuring details on various degree programs (B.Tech, M.Tech, PhD, Diploma), admission procedures, and campus news.

## Features

* **Course Information:** Dedicated pages for B.Tech (CSE, AI), M.Tech (IoT, Defense Electronics), and Diploma courses.
* **Student Resources:** Access to academic calendars, fee structures, and downloadable curriculum PDFs.
* **Faculty Profiles:** Directory of teaching staff with downloadable profiles.
* **Responsive Design:** Built using **Bootstrap** to ensure compatibility across devices.
* **Interactive UI:** Utilizes libraries like **OwlCarousel** for sliders and **WOW.js** for animations.

## Tech Stack

* **Frontend:** HTML5, CSS3, JavaScript
* **Framework:** Bootstrap (SCSS included)
* **Backend/Scripting:** PHP (Used for modular components like headers and footers)
* **Libraries:** Animate.css, Waypoints, OwlCarousel, Easing

## Project Structure

* **`/css` & `/scss`**: Stylesheets and Bootstrap source files.
* **`/js`**: Main JavaScript logic.
* **`/lib`**: Third-party plugins (animations, carousels).
* **`/pdf`**: Curriculums, brochures, faculty profiles, and regulation documents.
* **Root Directory**: Contains the main `.html` and `.php` pages (e.g., `index.php`, `about.html`, `contact.php`).

## How to Run

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/chandanxp/nielit-ropar-university.git](https://github.com/chandanxp/nielit-ropar-university.git)
    ```
2.  **Server Requirement:**
    Because the project utilizes `.php` files (e.g., `header.php`, `nav.php`) for including common layout elements, it is recommended to run the project using a local server environment such as:
    * **XAMPP / WAMP / MAMP**
    * **PHP Built-in Server** (`php -S localhost:8000`)
3.  **Static Fallback:**
    The project also contains `.html` versions of many pages (e.g., `index.html`). These can be opened directly in a web browser, though they may not reflect dynamic changes made in the PHP components.
