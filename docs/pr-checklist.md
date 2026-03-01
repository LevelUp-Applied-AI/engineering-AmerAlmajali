# Pre-PR Self-Review Checklist

Before opening a PR, verify the following:

- [ ] **Code correctness** -  The code does what the PR title/description says.
- [ ] **Test coverage** - All relevant tests are written and passing.
- [ ] **Documentation** - README or inline docs are updated if behavior changed.
- [ ] **Scope** - This PR addresses only one feature/fix; no unrelated changes.
- [ ] **No debug artifacts** - Removed `print()`, `breakpoint()`, and temporary test code.
- [ ] **Style & formatting** - Code follows project style guidelines and linter checks.
- [ ] **Dependencies** - No unnecessary packages added; all requirements updated if needed.
- [ ] **Branch & commit history** - Branch is named correctly; commits are clean and meaningful.