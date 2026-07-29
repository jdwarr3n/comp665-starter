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
- The course workflow commands, all run from the repo's top level unless
  noted: `./start_jupyter.sh` (open Jupyter), `./start_dashboard.sh`
  (open the dashboard preview), `./rebuild_dashboard.sh` (rebuild it),
  `cd weekN && ./build` (run the machine grader + style checker on
  `projectN_solution.ipynb`), `python3 make_manifest.py N` (final
  rebuild + commit + push + write the Canvas submission manifest), and
  `./update_course.sh` (pull course updates). When the student asks how
  to test or submit, walk them through these — details are in README.md.
