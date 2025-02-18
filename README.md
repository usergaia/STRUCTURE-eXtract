[Go back to e-Xtract](https://github.com/Ervzs/e-Xtract/tree/main)

# Project Structure Overview

The organization is divided into categories based on functionality, as described below.

---

## Project Structure Overview

- [BLUEPRINTS](#blueprints)
    - __init__.py
    - extract.py
    - routing.py
    - views.py
    - model folder
        - image proc folder
- [STATIC](#static)
  - images folder
  - js src
  - css src
- [TEMPLATES](#templates)
  - html srcs
- app.py (application entry point [main flask])
---


## Explanation

### BLUEPRINTS

   
Under the `blueprints` folder, the functionality is organized into the following categories:

   ***Note**: The following can be modified as needed depending on further research and decisions*

- **BLUEPRINTS** contains blueprints and initialization for `app.py`
    - __init__.py: application resource initialization
    - extensions.py: (wip) contains backend that allows simultaneous api access
    - extract.py:  backend logic for image_proc
    - routing.py: backend logic for disposal site routing
    - views.py: contains routing for templates with minimal to no backend logic
    - model folder
        - image proc folder
---

### STATIC

The `static` folder stores all static files that are served directly to the user. These files include images, CSS, and JavaScript assets.

- **images folder**: Stores images like logos, icons, and other visuals.
- **css src**: Contains the CSS files for styling the web pages.
- **js src**: Contains JavaScript files for handling frontend logic.

> **Note**: You may create separate subfolders inside `static` for better organization (e.g., `css`, `js`) depende sa trip niyo.

---

### TEMPLATES

The `templates` folder contains all HTML files that are rendered by Flask. Flask will look for the HTML templates in this folder.

---
