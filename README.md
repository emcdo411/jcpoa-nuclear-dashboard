# 📊 JCPOA Nuclear Dashboard

[![R](https://img.shields.io/badge/-R-276DC3?logo=r)](https://www.r-project.org/)
[![Shiny](https://img.shields.io/badge/-Shiny-1abc9c?logo=rstudio)](https://shiny.posit.co/)
[![Plotly](https://img.shields.io/badge/-Plotly-d62728)](https://plotly.com/)
[![Leaflet](https://img.shields.io/badge/-Leaflet-88cc88?logo=leaflet)](https://leafletjs.com/)
[![DT](https://img.shields.io/badge/-DT-33a02c)](https://rstudio.github.io/DT/)
[![dplyr](https://img.shields.io/badge/-dplyr-1f77b4)](https://dplyr.tidyverse.org/)
[![htmlwidgets](https://img.shields.io/badge/-htmlwidgets-9467bd)](https://www.htmlwidgets.org/)
[![shinyWidgets](https://img.shields.io/badge/-shinyWidgets-ff69b4)](https://github.com/dreamRs/shinyWidgets)
[![shinyjs](https://img.shields.io/badge/-shinyjs-006400)](https://deanattali.com/shinyjs/)
[![bslib](https://img.shields.io/badge/-bslib-5f9ea0)](https://rstudio.github.io/bslib/)
[![lubridate](https://img.shields.io/badge/-lubridate-c44e52)](https://lubridate.tidyverse.org/)

---

## 📦 Tech Stack & Installed Packages

**Languages & Frameworks**:

* R, Shiny, shinydashboard, shinydashboardPlus

**Visualization & Maps**:

* Plotly, Leaflet, DT

**Utility & Styling**:

* dplyr, shinyWidgets, shinyjs, bslib, htmlwidgets, lubridate

---

## 🔧 Installation

```r
install.packages(c("shiny", "shinydashboard", "shinydashboardPlus", "leaflet",
                   "plotly", "dplyr", "DT", "shinyWidgets", "shinyjs",
                   "bslib", "htmlwidgets", "lubridate"))
```

Clone the repository:

```bash
git clone https://github.com/your-username/jcpoa-nuclear-dashboard.git
```

Launch the app:

```r
shiny::runApp("jcpoa-nuclear-dashboard/app.R")
```

---

## 📈 Usage

* Navigate the dashboard tabs: Overview, Data Table, Centrifuge Insights
* Interact with year range, site filters, toggle satellite view/inspections/strikes
* Click chart points for enrichment or sanction modal popups
* Export nuclear site data via CSV, Excel, PDF
* Deploy via `rsconnect::deployApp()` for public use

---

## 💡 Why This Matters

This R Shiny dashboard allows data scientists, policy analysts, and AI/ML practitioners to explore real-world geopolitical data through interactive charts and spatial maps. It contextualizes complex enrichment, strike, and sanction data into a modern, stylized application for discovery and learning.

---

## ✅ Contributing & License

### Contributing

1. Fork the repository
2. Create a new branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Add new feature"`
4. Push to GitHub: `git push origin feature/your-feature`
5. Open a pull request

### License

MIT License. See `LICENSE` file for details.

---

## 📃 Full Source Code

> The full app source code is available in the `app.R` file within this repository. Please open `app.R` in RStudio or any text editor to view and copy the complete implementation of the JCPOA Nuclear Dashboard, including UI, server logic, CSS, plots, and interactivity.

If you'd like, the code can be copy-pasted directly from `app.R`, or feel free to ask to view it all embedded in this README.

