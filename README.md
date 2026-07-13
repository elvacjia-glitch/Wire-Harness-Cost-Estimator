Wire Harness Cost Estimator
A mobile-first B2B wire harness cost estimator built for LinkedIn lead generation. The tool gives international buyers a fast budgetary price range, then routes serious inquiries into a quote request flow.

Overview
This project is a single-file static website designed for GitHub Pages deployment. It is intended for wire harness exporters who want a lightweight, no-backend landing page that:

helps buyers estimate a rough landed cost range
frames results as budgetary reference rather than a formal quote
captures lead information after the estimate step
works well inside the LinkedIn in-app browser
Features
Single-file HTML + CSS + JS deployment
English buyer-facing copy for US, European, and Australian audiences
Mobile-first responsive layout
Static front-end estimation logic with no database and no backend
Application-specific pricing multipliers for:
Industrial Automation
RV & Marine
Data Center
Medical Device
EV High-Voltage
Lead capture flow after result display
Open Graph and social preview support for LinkedIn sharing
Hidden local setup mode for Formspree configuration
Project Structure
index.html — complete estimator page, UI, calculator logic, and lead-capture flow
og-preview.svg — social preview image for LinkedIn and other platforms
.nojekyll — ensures GitHub Pages serves the site as plain static files
How It Works
The estimator uses hardcoded public-market logic rather than factory purchasing data.

The displayed range is based on:

wire gauge factor
conductor count
wire length
connector tier benchmark
pins per connector
special processing selections
quantity tier
application-specific multiplier range
The result is intentionally broad and should be treated as a budgeting reference only.

Lead Capture Setup
You do not need to edit the HTML file just to activate quote-request submissions.

After the site is published, open:

https://your-site-url/?setup=1

Then save:

your Formspree endpoint
your business email
your company name
This setup is stored locally in that browser.

Deploy to GitHub Pages
Create a new GitHub repository.
Upload all files from this folder to the repository root.
Open Settings -> Pages.
Under Build and deployment, choose Deploy from a branch.
Select branch main and folder / (root).
Save and wait for the GitHub Pages URL.
LinkedIn Use Case
This tool is not meant to be embedded directly inside LinkedIn as an interactive widget.

Recommended usage:

add the GitHub Pages URL to your LinkedIn Featured section
include the link in posts, newsletters, or articles
let LinkedIn pull the Open Graph tags and show og-preview.svg as the share card
Notes
This tool does not generate formal quotations.
Freight is excluded by design.
Results are intentionally shown as a range, not a single price.
Lead submission will not work until your Formspree endpoint has been configured.
