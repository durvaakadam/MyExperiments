# MyExperiments — Engineering Lab Experiments

This repository contains collections of engineering lab experiments, organized by semester and lab. It's intended as a single place to store lab reports, code, configuration, diagrams, and small projects created during undergraduate engineering lab courses.

## Structure

Top-level folders (present in this workspace):

- `Semester 5/`
  - `ADL LAB/`, `DEVOPS LAB/`, `IP LAB/`, `SL LAB/`
- `Semester 6/`
  - `BI LAB/`, `DSL LAB/`, `MAD LAB/`, `WL LAB/`
- `Semester 7/`
  - `AIML/` (contains `AIML_8`), `DSL/`, `SADL/`

Each lab folder should contain one subfolder per experiment. Example:

```
Semester 6/
  DSL LAB/
    Experiment-01-Data-Model/
      report.pdf
      code/
      README.md
    Experiment-02-Queries/
      README.md
```

## What to put in each experiment folder

- `README.md` — short description of the experiment: objective, tools used, how to run code or reproduce results.
- `report.pdf` or `report.md` — lab report or notes.
- `code/` — any source code, scripts, notebooks. Include a `requirements.txt` or `environment` file when appropriate.
- `data/` — sample input data (if allowed by course rules).

## Lab README template

Use this template inside each experiment folder (create `README.md`):

- Title: Experiment name
- Objective: Short sentence about the goal
- Files: list of important files in the folder
- How to run: commands to run code (platform notes, e.g. Windows `cmd.exe`)
- Notes: observed results, references

Example:

```
Title: Experiment 01 — X
Objective: Demonstrate Y using Z tools.
Files:
  - code/ — implementation
  - report.pdf — writeup
How to run (Windows):
  1. Open `cmd.exe` in this folder
  2. Run `python -m venv .venv` then activate and install `pip install -r code/requirements.txt`
  3. Run `python code/main.py`

Notes:
  - Any special observations or grading notes
```

## Conventions

- Name experiment folders with a numeric prefix (e.g., `Experiment-01-Name`) so they sort chronologically.
- Keep large generated files (VM images, large datasets) out of the repo. Add them to cloud storage and link from a small metadata file.
- Add a per-lab `README.md` describing the lab and instructor/course code.

## How to contribute

1. Create a branch named `add/<semester>-<lab>-<experiment>`.
2. Add your experiment folder, follow the template above.
3. Submit a pull request with a short description.

If you're an instructor: include grading rubrics or any special submission guidelines inside the lab folder.

## License

This repository currently has no license file. Add a `LICENSE` if you want to apply one (for example, MIT).

## Contact / Maintainer

Repository owner: the student or group who owns this workspace. For questions, open an issue or add a note in the lab's `README.md`.

---

Small, maintainable lab repositories are easier to navigate and reuse. If you'd like, I can also:

- Add a `LICENSE` (MIT) file
- Create a per-lab `README.md` template file under each semester automatically
- Standardize a `CONTRIBUTING.md`

If you want any of those, tell me which and I'll add them.
