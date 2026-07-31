# Portfolio Website

A simple personal portfolio website built with HTML and CSS. It presents a home section, an about section, and a contact section for Sai Abhiram.

## Features

- Responsive-friendly single-page layout
- Navigation links for `Home`, `About`, and `Contact`
- Hero section with a background image
- GitHub and WhatsApp contact buttons
- Clean static structure with no build step required

## Project Structure

```text
portfolio-website/
├── images/
│   └── image.png
├── index.html
├── style.css
└── README.md
```

## Quality Checks

There is no build step, but static quality checks run in CI (and locally) via npm:

```bash
npm ci
npm test            # runs all checks below
npm run lint:html   # html-validate
npm run lint:css    # stylelint
npm run lint:links  # linkinator (broken links/images)
npm run lint:a11y   # pa11y-ci (WCAG 2 AA) against a local server
```

## Customization

- Update the text in `index.html` to change the personal details.
- Replace `images/image.png` with your own background image.
- Edit `style.css` to adjust colors, spacing, fonts, and layout.

## Contact

- GitHub: https://github.com/saiabhiramyelloju
- Email: dev@abhiramportfolio.dpdns.org
- LinkedIn: https://linkedin.com/in/sai-abhiram-yelloju
