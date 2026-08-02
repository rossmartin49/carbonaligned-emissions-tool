# CarbonAligned - Climate Finance Research Tool 2026

> **CarbonAligned is an offline web application for investigating portfolio climate exposure, financed emissions, implied temperature rise, and 2030 alignment through embedded datasets and calculations performed in the browser.**

[![Platform](https://img.shields.io/badge/Platform-Web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Current-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/rossmartin49/carbonaligned-emissions-tool?style=flat-square)](https://github.com/rossmartin49/carbonaligned-emissions-tool)

---

<p align="center">
  <a href="https://rossmartin49.github.io/carbonaligned-emissions-tool/">
    <img src="https://img.shields.io/badge/Download-CarbonAligned%20Latest-brightgreen?style=for-the-badge" alt="Download CarbonAligned">
  </a>
</p>

> **[Download CarbonAligned](https://rossmartin49.github.io/carbonaligned-emissions-tool/)**

---

[Download Latest Build](https://rossmartin49.github.io/carbonaligned-emissions-tool/)

---

## What CarbonAligned Does

CarbonAligned provides a browser-based workspace for climate finance research and portfolio review. It combines financed emissions analysis, portfolio implied temperature rise, carbon budget evaluation, and 2030 alignment assessment in a single tool.

The workflow is suitable for both initial investigation and more organized portfolio analysis. Holdings can be entered one at a time or brought in from a CSV file, while what-if comparisons make it possible to examine alternative positions. The application also presents data quality scores and supports climate report exports. Since the data and calculations are built into the app, it can operate offline, with portfolios saved and reopened through browser localStorage.

---

## Capabilities

- Apply PCAF attribution when calculating financed emissions.
- Produce portfolio implied temperature rise estimates.
- Evaluate carbon budgets and gaps against 2030 alignment.
- Create holdings manually or load them from CSV files.
- Compare possible portfolio changes using what-if holding swaps.
- Examine data quality scores together with analysis outputs.
- Work with an embedded dataset containing 80 sample companies.
- Export downloadable reports for climate research.
- Access included methodology material, FAQs, resources, and onboarding guidance.
- Perform calculations locally in an offline browser session using embedded data.
- Save portfolios to browser localStorage and load them again later.

---

## Getting Started

### Download and open the application

1. Visit the [latest build](https://rossmartin49.github.io/carbonaligned-emissions-tool/).
2. Save or clone the repository if you need a local copy.
3. Open the application's main entry page in a modern web browser.

### Get the source with Git

```bash
git clone https://github.com/rossmartin49/carbonaligned-emissions-tool.git
cd REPO
```

Once the repository is available, open the web app's primary HTML file in your browser. The offline workflow does not require a server-side runtime.

---

## Using CarbonAligned

1. Open CarbonAligned in a web browser.
2. Begin with the onboarding tour, methodology information, or the supplied sample company data.
3. Enter holdings manually or import a portfolio CSV.
4. Analyze financed emissions through the PCAF attribution method.
5. Review implied temperature rise, 2030 alignment gaps, and carbon budgets.
6. Compare possible portfolio alternatives with what-if holding swaps.
7. Consider the data quality scores when evaluating the results.
8. Save the portfolio in browser localStorage or export a climate report.

### Importing a CSV portfolio

Create a CSV containing the supported portfolio holdings and select it through the portfolio upload control. Once the import is complete, verify the positions and make any necessary changes before starting the analysis.

---

## Portfolio Storage and Configuration

CarbonAligned is controlled from its browser interface and does not use a server configuration file. Portfolio information and saved sessions are kept in the browser's localStorage.

To work with another portfolio:

1. Open the application using the same browser profile.
2. Upload a different CSV or add the new holdings manually.
3. Use the available save control, or follow the prompt, to store the revised portfolio.

Removing the app's browser storage also removes portfolios saved locally by the application.

---

## System Requirements

- A modern web browser.
- JavaScript turned on.
- Browser local storage enabled when saving and loading portfolios.
- Internet access when opening the hosted build link.
- No backend service or additional runtime is required for the offline application workflow.
- Enough local disk space for the downloaded web files and exported reports.

---

## Frequently Asked Questions

### What types of work is CarbonAligned intended for?

CarbonAligned is designed for climate finance research, portfolio analysis, ESG research, and carbon accounting work focused on financed emissions and investment alignment.

### Is offline use supported?

Yes. After the web app files are available locally, its embedded data and calculations allow CarbonAligned to be used offline.

### How do I enter a portfolio?

Holdings may be entered individually by ticker or imported from a CSV portfolio file.

### Where does CarbonAligned save portfolios?

Saved portfolios remain in localStorage for the browser and device profile used to create them.

### Can I investigate different holding choices?

Yes. The what-if holding swap capability lets you assess possible portfolio changes.

### How should I interpret the data quality score?

The score describes the quality of the data supporting a portfolio analysis. Use it as context alongside the calculated outputs and the methodology information.

### Where can I find the newest build?

Open [Download Latest Build](https://rossmartin49.github.io/carbonaligned-emissions-tool/) to reach the current hosted version.

### What if my portfolio fails to load properly?

Verify that the CSV follows the expected format, make sure JavaScript and local storage are enabled in the browser, and inspect the imported holdings before beginning the calculations.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
