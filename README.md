# New project template

<!--  What the project does; setup, run, and verification commands -->

## Create a project

From the template's parent directory, copy it to a new directory that does not already exist:

```sh
cp -a ./template ./new-project
```

This preserves the relative symlink `CLAUDE.md -> AGENTS.md`. Maintain `AGENTS.md`; both names show the same content. Each copied project has its own independent instructions.

The copy includes hidden files, local configuration, and any `.git` metadata. `.gitignore` does not filter what `cp` copies. Check the template for local secrets before copying, and do not carry template Git history into a project that should start with a fresh repository.

## New project checklist

- [ ] Define the project goal and intended users. Replace this README introduction with a short project description.
- [ ] Select the language, framework, and tools needed for the project.
- [ ] Document setup, development, and verification commands in this README. Confirm they work.
- [ ] Fill in `docs/DESIGN.md` with goals, requirements, constraints, non-goals, acceptance criteria, and open questions. Describe the current architecture as it takes shape.
- [ ] Set up CI early in the development process.
- [ ] Document the project structure in `AGENTS.md` and adapt its working rules to the project.
- [ ] Record significant design decisions in `docs/decisions/` and link to them from `docs/DESIGN.md`.
- [ ] Update `.gitignore` for the chosen stack and local secrets. Add an `.env.example` with placeholder values if configuration is needed.
- [ ] Remove unused placeholders, files, and directories. Keep progress notes only if they will be maintained.
- [ ] Remove this checklist once setup is complete. Keep the project description and commands current.
