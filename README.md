# Flask REST API Skeleton

This project is a best-practice skeleton for a Flask REST API.

## Structure

- `app/` - Application package
  - `__init__.py` - App factory
  - `routes.py` - API routes (Blueprint)
  - `models.py` - Database models
- `config.py` - Configuration
- `run.py` - Entry point
- `requirements.txt` - Python dependencies
- `.flaskenv` - Flask environment variables
- `.gitignore` - Git ignore rules

## Quickstart

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Run the app:
   ```bash
   flask run
   ```

## Extending
- Add new routes in `app/routes.py` or create new blueprints.
- Add models in `app/models.py`.
- Update configuration in `config.py`.