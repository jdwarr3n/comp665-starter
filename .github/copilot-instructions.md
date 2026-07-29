# COMP 665 — instructions for Copilot

- Develop solutions from the project description the student provides
  and the week's `projectN_template.ipynb`. Work in `projectN_solution.ipynb`.
- Do not read or analyze `projectN_checker.py`, `build`, `data/`, or
  expected-output files to infer answers — reverse-engineering the
  checker wastes time and is not the assignment.
- Use only the modules the template already imports; never install packages.
- Follow pylint conventions (the course configuration is `public/pylintrc`).
- Never edit the checkers, `public/`, `data/`, the environment files,
  or anything under `docs/` (generated).
## Course workflow commands

Run from the repo's top level, except `./build`:

| Command | What it does |
|---|---|
| `./start_jupyter.sh` | Open the Jupyter notebook server in a browser tab |
| `./start_dashboard.sh` | Open the dashboard preview in a browser tab |
| `./rebuild_dashboard.sh` | Rebuild the dashboard from the `weekN/` work |
| `cd weekN && ./build` | Run the machine grader + style checker on `projectN_solution.ipynb` |
| `python3 make_manifest.py N` | Rebuild, commit, push, and write the week's Canvas submission manifest |
| `./update_course.sh` | Pull the latest course updates |

When the student asks how to test or submit, walk them through these —
details are in README.md.
