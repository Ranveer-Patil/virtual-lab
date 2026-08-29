# AI Virtual Lab — Memory Technology Comparison

An interactive single-page virtual lab for comparing RAM and ROM technologies with simulated benchmarking, live charts, thermal impact modeling, and report export.

## Features
- RAM simulation for DDR4, DDR5, and LPDDR5 modules
- KPI summary for access time, power draw, cost/GB, and reliability
- ROM comparison across EEPROM, Flash NAND, and Flash NOR
- Analytics dashboard with multiple Chart.js visualizations
- Temperature impact lab with live performance degradation view
- Auto-generated insights and PDF report export

## Tech Stack
- HTML, CSS, and vanilla JavaScript
- [Chart.js](https://www.chartjs.org/) for charts
- [jsPDF](https://github.com/parallax/jsPDF) for PDF export

## Run Locally
This project is static and does not require a build step.

1. Clone the repository.
2. Open `/home/runner/work/virtual-lab/virtual-lab/index.html` in a browser.

Optional (recommended): serve it over a local HTTP server:

```bash
cd /home/runner/work/virtual-lab/virtual-lab
python3 -m http.server 8080
```

Then open `http://localhost:8080`.
