# LaTeX Resume Project

This repository contains a professional resume template built using LaTeX. The template is designed to be clean, modern, and easy to customize.

## Features
- Clean and professional design
- Customizable sections
- Consistent formatting
- Easy to modify and extend
- Proper spacing and alignment

## File Structure
- `main.tex`: Main document file
- `header.tex`: Header section
- `education.tex`: Education section
- `experience.tex`: Professional experience section
- `projects.tex`: Relevant academic projects section
- `coursework.tex`: Coursework section
- `cocurricular.tex`: Co-curricular activities section
- `structure.tex`: Custom commands and formatting

## Recent Updates
- Added hyperlinks to email and LinkedIn profile in header
- Fixed date alignment to right edge of page
- Implemented consistent 1.0 line spacing throughout
- Removed extra spacing at start/end of sections
- Fixed LaTeX errors in coursework section

## Instructions
1. Fill in your personal information in `header.tex`.
2. Update the sections in `education.tex`, `experience.tex`, `projects.tex`, `cocurricular.tex`, `coursework.tex` with your details.
3. Compile the `main.tex` file to generate your CV.

## Usage
1. Clone the repository
2. Modify the .tex files to add your content
3. Compile using a LaTeX editor or command line

## Requirements
- LaTeX distribution (e.g., TeX Live, MiKTeX)
- PDF viewer

## GitHub Actions Workflow

This repository uses a GitHub Actions workflow to automatically generate a PDF from the LaTeX source files and push the generated PDF to the repository.

### Setting Up the Workflow

To set up the workflow, follow these steps:

1. Create a Personal Access Token (PAT) on GitHub with the necessary permissions (Contents and Metadata).
2. Store the PAT as a secret in your GitHub repository:
   - Go to **Settings** > **Secrets** > **Actions**.
   - Click on **New repository secret**.
   - Name the secret `ACTIONS_PATH` and paste the PAT you copied earlier.

### Note

The GitHub Actions workflow file is configured to use the `ACTIONS_PATH` secret for authentication. Make sure to update the secret if you regenerate the PAT.

### Privacy of Actions

Please note that the actions taken in this repository are public and can be viewed by anyone with access to the repository. GitHub Actions logs and workflow runs are not private for public repositories.
