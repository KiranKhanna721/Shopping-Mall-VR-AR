# Shopping Mall VR/AR

A prototype Flask web storefront for a virtual shopping mall. It was built as the front end of a VR/AR shopping experience.

## Features

- Home page and a product catalogue
- Product pages for clothing (t-shirts and dresses in several colours, a party dress) and furniture (sofas, a dining table, a glass table, a table-and-sofa set)
- Shopping cart page
- Shared layout with custom CSS and JavaScript

## Project structure

| Path | Purpose |
|------|---------|
| `app.py` | Flask routes for the home, product, cart and individual item pages |
| `config.py` | App configuration |
| `templates/` | HTML pages |
| `static/` | CSS, JS and product images |
| `Procfile` | Heroku deployment (gunicorn) |

## Getting started

```bash
pip install -r requirements.txt
python app.py
```

Then open http://127.0.0.1:5000.
