# Data Directory

This directory contains all data files needed for the soccer analysis project.

## Directory Structure

- `raw/` - Original, unmodified data files
- `processed/` - Cleaned and processed data files
- `images/` - Source images used in visualizations
- `fonts/` - Font files for infographics

## Required Data Files

### SQLite Database
The main dataset should be placed in `raw/database.sqlite`

**Source:** European Soccer Database on Kaggle
- **URL:** https://www.kaggle.com/datasets/hugomathien/soccer
- **Description:** Contains data on over 10,000 European soccer players with attributes from 2008-2016

### Required Images (for `images/` directory)
- `messi.jpg` - Image of Lionel Messi
- `FIFA.png` - FIFA logo
- `soccer-field.jpg` - Soccer field background image

### Required Fonts (for `fonts/` directory)
- `fa-brands-400.ttf` - Font Awesome brands font
- `fa-solid-900.ttf` - Font Awesome solid icons font

**Font Source:** Font Awesome (https://fontawesome.com/)

## Setup Instructions

1. Download the European Soccer Database from Kaggle
2. Place `database.sqlite` in the `raw/` directory
3. Add required image files to the `images/` directory
4. Add Font Awesome font files to the `fonts/` directory

## Note

Data files are gitignored to keep the repository size manageable. Please download them separately before running the analysis.
