# LegacyFixer major update guard demo

This repository is used to test LegacyFixer's major update guard.

Expected behavior:

- LegacyFixer detects a vulnerable dependency
- pip-audit proposes a fix that upgrades the dependency across a major version
- because allow_major_updates is disabled, LegacyFixer does not open a pull request
- the job result explains that major updates were blocked

LegacyFixer major-update guard trigger.
