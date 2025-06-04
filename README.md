# GitHub Workflow Templates

This repository stores reusable workflow files for GitHub Actions.
These workflows automate common tasks such as linting, testing, and building.
They also manage releases.

## Included Workflows

- **Linting** for Markdown, prose, YAML, and shell scripts
- **Testing** of Python code using `pytest`
- **Formatting** checks via `black`
- **Security** scanning with CodeQL
- **Build** and **benchmark** steps
- Automated **releases** when tags are pushed

## Maintenance

All directories, including hidden ones, were checked. Yamllint reported
warnings for missing `---` headers and non-boolean truthy values. Add these
corrections to workflow files. Before making future updates, run the included
linting workflows (`yamllint`, `markdownlint`, and `proselint`) to catch
potential errors. Keep Markdown lines under 80 characters and ensure every
file ends with a newline.
