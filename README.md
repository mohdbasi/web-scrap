# Internshala Job Scraper

This project scrapes Python/Django job listings from [Internshala](https://internshala.com/jobs/python-django-jobs/), extracts details such as job title, company, location, skills required, experience, salary, job description, and job link, and saves them into a well-formatted Excel file.

## Features

- Scrapes job listings from Internshala.
- Extracts all relevant job details, including full job descriptions and required skills.
- Saves data to an Excel file (`Internshala_Jobs.xlsx`).
- Auto-adjusts column widths and wraps text for readability.
- Highlights the header row in bold.

## Requirements

- Python 3.8+
- See `requirements.txt` for required packages.

## Installation

1. Clone this repository or download the files.
2. Install dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Run the scraper script:
    ```sh
    python internshala_scraper.py
    ```
2. The output Excel file `Internshala_Jobs.xlsx` will be created in the project directory.

## Output

The Excel file will contain the following columns:
- JobTitle
- Location
- ExperienceRequired
- SkillsRequired
- Salary
- JobDescriptionSummary
- JobURL

All columns are auto-sized and text is wrapped for better readability.

## License

This project is for educational purposes.
