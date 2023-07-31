# My growth data

![License](https://img.shields.io/badge/license-Tome.gg%20Public%20Growth%20License-success)

## About

This repository leverages [Tome.gg](https://tome.gg)'s Librarian Protocol to 
structure the data entries in this repository.

By using the Librarian Protocol, Tome.gg tooling is able to parse and analyze your personal growth data, and generate meta-content such as the visual daily-progress summary presented above.

## Usage

1. Install the [Tome.gg Librarian CLI](https://github.com/tome-gg/librarian/releases) and add it to your path.
2. Use this GitHub repository as a template.
3. Edit `tome.yaml` to specify your repository `source` based on your git repository URL.
4. Start adding your training, practice, or daily-stand up reports on the `training/` directory.
5. After collecting data (e.g. 1 week), spend some time to evaluate yourself on `evaluations/self.yaml`.
6. Invite your mentors as contributors to your GitHub repository, and ask them to evaluate your work on `evaluations/mentor_name.yaml`.
7. Before committing your work to Git, use `tome validate .` to ensure that your repository passes the Tome.gg data and directory structure requirements.


## Optional reports
1. Edit `src/config.json` to specify your repository URL correctly, and specify which evaluations files will be used for the generated report.
2.  You can access generated visual progress reports (requires evaluations) from the GitHub actions tab, specifically the `generate-report` action.