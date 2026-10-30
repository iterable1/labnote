# Labnote — AI Lab Record Assistant

Labnote is a lightweight browser-based lab notebook for recording experiment details, observations, calculations, and conclusions. It is designed for practical work in schools, colleges, and research labs, with a simple note-taking layout and optional AI assistance for drafting and reviewing lab sections.

## Features

- Structured lab record layout for:
  - Experiment details
  - Objective
  - Apparatus and theory
  - Procedure
  - Observations
  - Calculations
  - Results and conclusion
- Dark mode for low-light working
- New blank record opened in a separate tab
- Editable sections for writing and revising entries
- Observation table for adding rows and recording values
- AI-assisted drafting and review using an API endpoint
- Export as HTML for saving or sharing
- Print/PDF support
- Add or remove custom sections when your experiment needs extra documentation

## How to use

### 1. Open the app

Open the file `lab_assistant.html` in any modern web browser.

You can also open it directly from GitHub by downloading the repository and loading the HTML file locally.

### 2. Start a new record

- Click the `New record` button in the top bar to open a fresh blank lab record in a new tab.
- This keeps your current page intact and creates a clean notebook for a new experiment.

### 3. Fill in experiment details

In the main document area, enter:

- Student name
- Roll number
- Course/subject
- Date
- Experiment number
- Experiment title

### 4. Complete each section

Use the editable fields to write:

- Objective
- Apparatus and theory
- Procedure
- Observation notes
- Calculations
- Result and conclusion

You can type directly into the page, add rows to the observation table, and update your content as needed.

### 5. Add or remove custom sections

If your practical requires extra sections, click `Add section` in the left-side navigation. Enter a title in the dialog and choose `Add section`.

- The new section appears in the document and navigation menu.
- Use its visible `Remove section` button to delete it and its navigation entry.
- You can rename a custom section by editing its heading.

This makes the notebook flexible for experiments that need extra notes, safety checks, or observations beyond the default lab template.

### 6. Use dark mode

Click the `Dark` toggle in the top-right area to switch between light and dark themes.

### 6. Use AI assistance (optional)

In the right-side panel, under AI connection settings, enter:

- API key
- API endpoint
- Model name

Then you can:

- Ask AI to draft a section
- Review the whole document
- Improve writing clarity
- Check completeness and missing details

Important: AI suggestions should be reviewed before being applied. Do not trust generated content blindly, especially for real measurements or results.

### 7. Export or print

Use the toolbar buttons to:

- Print / PDF the record
- Export the record as HTML

This is useful for saving a copy or sharing the lab notebook outside the browser.

## Notes on safety and accuracy

- The app is designed for recording your own experimental work.
- AI-generated text may be helpful but should always be checked for scientific accuracy.
- Never invent measurement values or experimental outcomes.
- Use placeholders when exact data is missing.

## Recommended workflow

1. Open a fresh record.
2. Fill in metadata and experiment title.
3. Record objective, apparatus, procedure, and observations as you work.
4. Add calculations and final conclusions after analysis.
5. Export, print, or save the final notebook.

## Local setup

This project does not require a server or installation. It is a standalone HTML file and works directly in a browser.

## License

This project is provided as-is for educational and personal use. Please check your local institutional or academic policy before using it in official coursework or laboratory submissions.
