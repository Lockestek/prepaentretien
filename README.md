# Prépa Entretien

A lightweight static website that organizes interactive interview-preparation
material into Finance and Product Management collections.

## Current scope

- A landing page with dedicated **Finance** and **Product** categories.
- Four interactive Finance courses covering payments, compliance, data and AI,
  and digital insurance.
- Six Product Management courses covering market research, go-to-market,
  P&amp;L ownership, pricing, revenue ownership, and Voice of Customer.

## Project structure

```text
.
├── finance/        # Finance course HTML files
├── product/        # Product Management course HTML files
├── index.html      # Main website page and course directory
├── styles.css      # Landing-page styling
└── README.md       # Project notes
```

## Usage

Open `index.html` in a browser and select a course from either category. The
site requires no build step or external dependencies.

When adding material, place its HTML file in the matching `finance/` or
`product/` folder and add a resource card to `index.html`. Links from a course
back to the home page must use `../index.html`.
