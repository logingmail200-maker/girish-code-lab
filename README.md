# Girish’s Code Lab

A personal portfolio for Girish Kumar, a first-year CSE student at BMSCE (2026–2030).

Repository: https://github.com/logingmail200-maker/girish-code-lab

Featured project: https://wherewas.onrender.com/

## Preview
Run `python -m http.server 8088 --bind 127.0.0.1` in this folder, then open http://127.0.0.1:8088/.
No installation or build step is required.

## Files
- index.html: portfolio content and accessible page structure
- assets/styles.css: responsive styling, focus states, reduced-motion support
- assets/lab.js: three-step interactive lab and restart behavior
- assets/wherewas-preview.png: screenshot from the existing WhereWas project
- assets/favicon.svg: site icon

## Interaction
Visitors choose the HTML heading tag, CSS background property, and Python loop count. Correct answers update the workspace and progress indicator. Wrong answers give a retry hint. A restart button resets the experience. The Python example is a code-tracing question; no Python interpreter runs in the visitor’s browser.

## Deployment
Static site suitable for AWS Amplify Hosting. Upload the prepared ZIP with index.html at its root. No backend, database, API keys, or environment variables are needed. Fonts use Google Fonts with local system fallbacks.

## Project accuracy and assistance
WhereWas is presented as a prototype. Its London demonstration is illustrative and is not a measured engine result. This portfolio was developed with AI coding assistance; Girish should review the code and describe his own learning accurately in the submission. AWS deployment is still pending.
