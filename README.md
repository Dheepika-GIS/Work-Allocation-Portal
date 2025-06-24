# Work Allocation Portal QGIS Plugin

This plugin provides a custom interface for managing GIS-based work allocation with:
- Role-based field-level editing
- Integrated PostgreSQL backend
- Inline spreadsheet-like editing
- Undo/Redo and group editing
- Custom filters, zoom to features, and more

## Features
- View and edit assigned work units
- Restrict field access based on user role
- Paste from clipboard like Google Sheets
- Realtime updates to PostgreSQL

## Requirements
- QGIS 3.22+
- PostgreSQL with required schema and tables
- Python libraries: `PyQt5`, `qt_pysheet`, `psycopg2`, `pandas`

## Installation
1. Clone or download the repo.
2. Copy the plugin folder to your QGIS plugin directory.
3. Enable it from QGIS Plugin Manager.
