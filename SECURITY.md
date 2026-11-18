# Security policy

## Reporting a vulnerability

Please report security problems privately, not in a public issue.

- Preferred: open the **Security** tab of this repository and choose **Report a vulnerability**.
- Otherwise: send me a message at https://www.linkedin.com/in/aditya12t.

Include what you found, how to reproduce it, and the impact you expect.
I aim to reply within 7 days.

## Scope

This repository is a portfolio project. It is a static page with no forms, no server and no stored data; it holds no real
customer data, credentials or secrets. Reports about the code in this repository are in scope;
reports about third-party services it depends on should go to those projects.

## How this repository is protected

- Code scanning (CodeQL) of the page script on every push and weekly.
- A Content Security Policy lets the browser run only this page's own script and load only its fonts.
- Secret scanning with push protection blocks committed credentials.
