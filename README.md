# MathEdu Maroc

**MathEdu Maroc** is a free, open-source worksheet generator for mathematics in Moroccan middle schools (collège).

## Current prototype

| Level | Worksheet topics |
| --- | --- |
| 1ère année collège | Decimal arithmetic; addition and subtraction of fractions with equal denominators |
| 2ème année collège | Addition and subtraction of signed numbers; comparison of rational numbers |

- Generate 1 to 30 randomized questions.
- Show or hide answers with short explanations.
- Print or save worksheets as PDF through the browser.
- No account, server, or personal student data required.

## Run locally

Download the repository and open `index.html` in a modern browser. No build tools required.

## GitHub Pages

This project includes an automatic GitHub Pages deployment workflow at `.github/workflows/pages.yml`. Under **Settings → Pages → Build and deployment**, select **GitHub Actions** as the source. Check the **Actions** tab for deployment status. Once deployed, the expected URL is:

https://kamaldaghouti.github.io/mathedu-maroc/

The existence of this URL does **not** by itself confirm successful deployment.

## Quality and limitations

This is an early prototype, not a curriculum-validated teaching resource. The current lessons cover only a small portion of the Moroccan curriculum. Answers and worked explanations should be checked by a mathematics teacher before use in class. The UI is French only; Arabic translation, accessibility review, and automated tests are still planned.

See [QUALITY_CHECKLIST.md](QUALITY_CHECKLIST.md) for a manual verification plan.

## Contribute

Please read [CONTRIBUTING.md](CONTRIBUTING.md). Contributions, bug reports, teaching feedback, accessibility improvements, and Arabic translations are welcome.

## License

[MIT](LICENSE).
