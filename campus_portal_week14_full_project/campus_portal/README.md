# Campus Portal — PC15 Week 14

A small Django student portal demonstrating Django Template Language (DTL),
template inheritance, reusable navigation, static CSS/images, and accessible links.

## Run locally

1. Install Python 3.10+.
2. Open a terminal in this project folder.
3. Create and activate a virtual environment (recommended).
4. Install dependencies:

   ```bash
   python -m pip install -r requirements.txt
   ```

5. Start the development server:

   ```bash
   python manage.py runserver
   ```

6. Visit:
   - Home: http://127.0.0.1:8000/
   - About: http://127.0.0.1:8000/about/

## Project structure

- `campus_portal/` — Django project configuration
- `portal/` — app, views, URL routes, templates, and static assets
- `portal/templates/portal/base.html` — shared page layout
- `portal/templates/portal/partials/navbar.html` — reusable navigation
- `portal/static/portal/css/style.css` — external stylesheet
- `portal/static/portal/images/logo.png` — local logo image

## Accessibility checks to perform

- Use Tab and Shift+Tab to move through Home and About links.
- Confirm the keyboard focus indicator is visible.
- Resize the browser to a narrow/mobile width and verify the navigation wraps.
- Check that the logo has descriptive alternative text.

This project is a starter submission. Add your own name/section details and capture
your own screenshots and demonstration video after running it.
