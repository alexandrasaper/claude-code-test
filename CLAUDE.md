# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a single-file web project. All code lives in `tictactoe.html` — HTML, CSS, and JavaScript are co-located in one file with no build step or dependencies.

## Running the Project

Open the file directly in a browser:
```bash
open tictactoe.html
```

## Git & GitHub

**Commit and push after every meaningful change.** Never leave work uncommitted — each logical unit of work (new feature, bug fix, config change) should be its own commit so progress is never lost and can always be reverted.

```bash
git add <files>
git commit -m "short imperative summary

Optional body explaining why, not what."
git push
```

- Commit messages should be clear and specific (e.g. `"Add win animation to Tic Tac Toe"`, not `"update"`)
- Push to `origin/main` after every commit
- Remote: `https://github.com/alexandrasaper/claude-code-test`
