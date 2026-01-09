# DataMigration

## Overview
A static HTML website for an Accounting Migration Platform UI. This is a multi-page data migration interface that allows users to manage migrations between different accounting systems.

## Project Structure
- `Index.html` - Main entry point with navigation sidebar
- `Dashboard Screen.html` - Migration overview dashboard
- `migration_history.html` - View migration history
- `migration_execution.html` - Execute migrations
- `migration_details_view.html` - View migration details
- `new_migration__*.html` - Multi-step new migration wizard pages
- `server.py` - Python HTTP server for serving static files

## Technology Stack
- HTML/CSS with Tailwind CSS (via CDN)
- Python 3.11 for static file serving

## Running the Application
The application runs on port 5000 using a simple Python HTTP server:
```
python server.py
```

## Deployment
Configured for static deployment serving the HTML files.
