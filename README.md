# ArchComply

ArchComply is a web-based tool designed to assist with the archiving and destruction of physical files for Fletchers Solicitors ([fs.co.uk](https://fs.co.uk/) / [fletcherssolicitors.co.uk](https://www.fletcherssolicitors.co.uk/)). It helps users calculate the correct destruction date for archived files, ensuring compliance with legal and regulatory retention requirements.

## Purpose

This tool streamlines the process of determining when physical files can be safely destroyed, based on:
- The date of birth (DOB) of the subject, **or** their age and a reference date
- The file closure date
- The required retention period (in years)

It is especially useful for legal, compliance, and records management teams handling sensitive or regulated documents.

## Features

- **Destruction Date Calculator**: Enter DOB or age, file closure date, and retention period to get the destruction date.
- **18th Birthday Calculation**: Automatically determines the 18th birthday, which is often a key date for retention policies.
- **Clipboard Support**: Optionally copies the result to your clipboard for easy record-keeping.
- **User-Friendly Interface**: Simple, accessible form with keyboard navigation hints.

## Usage

1. Open `destruction-date-calculator/destruction-date-calculator.html` in your web browser.
2. Choose whether to enter a Date of Birth or an Age with a reference date.
3. Enter the required details:
	- DOB or Age + Reference Date
	- File closure month and year
	- Retention period (years)
4. Click **Calculate Destruction Date**.
5. The tool will display:
	- The calculated destruction date (month and year)
	- The 18th birthday (day, month, year)
6. If enabled, the destruction date is copied to your clipboard automatically.

## Example

Suppose a file relates to a person born on 15-08-2000, the file was closed in 03-2022, and the retention period is 7 years. The tool will calculate the correct destruction date based on these inputs.

## Project Structure

- `destruction-date-calculator/` — Main HTML file for the calculator
- `resources/styles/` — CSS styles
- `resources/images/logo/` — Project logos

## Requirements

This is a static web tool. No installation or backend is required. Simply open the HTML file in any modern web browser.

## License

This project is intended for internal use at Fletchers Solicitors. Please contact for licensing or usage outside the organization.