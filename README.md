# Strata Levy Projection Planner

A Progressive Web App (PWA) for modelling long-term strata finances,
levy strategies, reserve funding, and major capital works.

## Features

-   📊 5-year financial projections
-   🏦 Separate Admin and Reserve fund modelling
-   💰 Ordinary levy and Special levy modelling
-   📅 Monthly, quarterly, or annual special levy options
-   🏗 Planned major works scheduling
-   📈 Construction and operating cost inflation assumptions
-   🎯 Target reserve balance with automatic levy rebalancing
-   ⚖ Scenario comparison (Owner First, Balanced Recovery, Accelerated
    Renewal)
-   🤖 Automatically generated scenario interpretation and
    recommendations
-   📄 Professional PDF report export
-   📱 Progressive Web App (installable on desktop and mobile)

## Project Structure

    index.html
    manifest.json
    service-worker.js
    icon-192.png
    icon-512.png

## Deploying to GitHub Pages

1.  Create a new GitHub repository.
2.  Upload all project files to the repository root.
3.  Go to **Settings → Pages**.
4.  Set:
    -   **Source:** Deploy from a branch
    -   **Branch:** `main`
    -   **Folder:** `/ (root)`
5.  Save and wait a minute or two for deployment.

Your app will be available at:

    https://YOUR_USERNAME.github.io/REPOSITORY_NAME/

## Installing the App

### Android (Chrome/Brave)

Open the GitHub Pages URL and choose:

**Menu → Add to Home Screen**

or

**Install App**

### Desktop

Most Chromium-based browsers will show an **Install** button in the
address bar.

## Financial Model

The planner models:

-   Current Admin Fund
-   Current Reserve Fund
-   Current cash balance
-   Levy arrears
-   Number of lots
-   Ordinary levy allocation
-   Special levy schedules
-   Planned capital works
-   Operating expense inflation
-   Construction inflation
-   Reserve target maintenance

Once the reserve target has been achieved after major works, the planner
can automatically rebalance ordinary levy allocations between the
Reserve and Admin Funds while maintaining the target reserve.

## Disclaimer

This tool is intended to support planning and discussion by strata
councils and owners. It is **not** a substitute for professional
engineering, accounting, quantity surveying, or legal advice.

Financial projections are based on user-provided assumptions and should
be validated against current contractor quotations, engineering reports,
and the latest strata financial statements before making funding
decisions.

## Future Ideas

-   10-year projection mode
-   Strata loan modelling
-   Monte Carlo / sensitivity analysis
-   Multiple reserve strategies
-   Import/export project files
-   Live chart dashboards
-   Multi-building support
