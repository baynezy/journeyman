# GitHub Copilot Instructions

This document contains guidelines that GitHub Copilot should follow when assisting with this repository.

## General

* Make only high confidence suggestions when reviewing code changes.
* Infer the naming conventions and coding standards from the existing codebase.
* Prefer UK English spelling for all text, including comments and documentation.

## Changelog Updates

For all Pull Requests created:

1. **An entry must be added to CHANGELOG.md** under the `[Unreleased]` section.
2. Entries should follow the [Keep a Changelog](https://keepachangelog.com/en/1.0.0/) format.
3. Group changes under the appropriate headings:
   - `Added` for new features
   - `Changed` for changes in existing functionality
   - `Deprecated` for soon-to-be removed features
   - `Removed` for now removed features
   - `Fixed` for any bug fixes
   - `Security` in case of vulnerabilities
4. Be concise but descriptive in the changelog entries.
5. Make sure the entry clearly communicates the purpose and impact of the change.
6. Add a reference to the issue number if applicable.

This changelog update is required for all PRs to maintain a comprehensive history of changes to the project.