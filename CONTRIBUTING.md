# Contributing

Thanks for taking the time to contribute. The project is a single-file web application, so contributions are straightforward to make and review.

## Reporting Bugs

Before opening an issue, check whether the bug is already reported. When filing a new one, include:

- What you expected to happen
- What actually happened
- Steps to reproduce (input values, which tab, which browser)
- Browser name and version
- Device type (desktop, tablet, phone)

You can also use the contact form at the bottom of the page for informal reports.

## Requesting Features

Open an issue with the label `enhancement` and describe:

- The statistical method or calculator feature you want
- A brief description of the inputs and expected outputs
- A reference (textbook, Wikipedia, paper) if applicable for verification

## Making Changes

1. Fork the repository and clone your fork.
2. Create a branch: `git checkout -b feature/your-feature-name`
3. Make your changes in `index.html`.
4. Open `index.html` in a browser and test your changes manually across the affected calculator tabs.
5. Check that existing calculations still produce correct results.
6. Commit with a clear message describing what changed and why.
7. Push your branch and open a pull request against `main`.

## Code Style

- All logic lives in `index.html` — keep it that way unless there is a compelling reason to split.
- JavaScript: no frameworks or external libraries. Prefer readable over clever.
- CSS: follow the existing naming conventions and color palette.
- Mathematical implementations should cite a reference (formula, approximation source) in a comment if the derivation is non-obvious.
- Do not add comments that restate what the code does — only add them when the *why* is not obvious.

## Verifying Math

For new distributions or statistical functions, verify outputs against a trusted source (R, Python's `scipy.stats`, Wolfram Alpha, or a textbook table) before submitting. Include a verification note in the PR description.

## Pull Request Checklist

- [ ] Changes tested in Chrome, Firefox, or Safari
- [ ] Tested on a mobile viewport (DevTools responsive mode is fine)
- [ ] No new external dependencies introduced
- [ ] Mathematical results spot-checked against a reference
- [ ] PR description explains what changed and why
