# R/Pharma 2025 Conference Materials

[![Website](https://img.shields.io/badge/Website-Live-blue?style=flat-square)](https://actn3bioinformatics.github.io/R-Pharma-2025-Workshops/) [![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE) [![Quarto](https://img.shields.io/badge/Made%20with-Quarto-75AADB?style=flat-square&logo=quarto)](https://quarto.org)

> Comprehensive documentation of R/Pharma 2025 conference workshops, presentations, and insights.

**📍 View the full site:** [actn3bioinformatics.github.io/R-Pharma-2025-Workshops](https://actn3bioinformatics.github.io/R-Pharma-2025-Workshops/)

------------------------------------------------------------------------

## 📊 Quick Stats

-   **19** Hands-on Workshops
-   **8** Europe/US Thematic Sessions
-   **30+** Presentations
-   **November 2025** Conference Date

## 🔥 Top Themes

-   🤖 **AI & LLM Integration** - 8+ sessions on artificial intelligence in pharma R workflows
-   📊 **Clinical Reporting** - Modern approaches to TLGs, CSRs, and regulatory submissions
-   ✅ **Validation & Compliance** - GxP-ready R solutions and regulatory acceptance
-   🚀 **Open Source Adoption** - Industry shift from proprietary to open-source tools

## 🎯 What's Inside

### [📚 Workshops](https://actn3bioinformatics.github.io/R-Pharma-2025-Workshops/workshops/)

Detailed documentation of 19 workshops covering:

-   **AI & LLM** - Getting started with `{ellmer}`, building agentic systems, privacy-preserving implementations
-   **Clinical Reporting** - `{officer}`, `{flextable}`, `{cardinal}`, `{gtsummary}`, Quarto
-   **Development & Validation** - Package building, validation frameworks, `{datasetjson}`
-   **Statistical Methods** - Stan debugging, Bayesian approaches, `{rpact}`, `{tidymodels}`
-   **Specialized Apps** - `{teal}`, SDTM programming, Python for CSR, HPC integration

### [🎤 Presentations](https://actn3bioinformatics.github.io/R-Pharma-2025-Workshops/presentations/)

Summaries from:

-   8 Europe/US thematic sessions
-   13 Asia/Pacific presentations
-   Topics from AI agents to GSK's open-source journey

### [💡 Insights & Analysis](https://actn3bioinformatics.github.io/R-Pharma-2025-Workshops/summary/trends-insights.html)

-   **Trend Analysis** - AI revolution, open-source momentum, regulatory evolution
-   **Tools Catalog** - A-Z reference of all mentioned packages and technologies
-   **Career Guidance** - Skills demand, transition strategies, contribution opportunities

## 🚀 Quick Start

### View the Website

Visit: [**actn3bioinformatics.github.io/R-Pharma-2025-Workshops**](https://actn3bioinformatics.github.io/R-Pharma-2025-Workshops/)

### Build Locally

``` bash
# Clone the repository
git clone https://github.com/ACTN3Bioinformatics/R-Pharma-2025-Workshops.git
cd R-Pharma-2025-Workshops

# Install Quarto (if not already installed)
# Download from: https://quarto.org/docs/get-started/

# Render the site
quarto render

# Preview locally
quarto preview
```

The site will be available at `http://localhost:4200`

## 📁 Repository Structure

```         
.
├── _quarto.yml              # Quarto configuration
├── index.qmd                # Home page
├── styles.css               # Custom styling
├── workshops/               # Workshop documentation
│   ├── ai-llm/
│   ├── clinical-reporting/
│   ├── development-validation/
│   ├── statistical-methods/
│   └── specialized/
├── presentations/           # Presentation summaries
│   ├── europe-us-sessions.qmd
│   └── asia-pacific-sessions.qmd
├── summary/                 # Analysis and insights
│   ├── trends-insights.qmd
│   ├── tools-catalog.qmd
│   └── career-insights.qmd
└── about.qmd               # About this project
```

## 🌟 Featured Content

### Most Popular Workshops

-   [**Getting Started with LLM APIs in R**](workshops/ai-llm/getting-started-llm-apis.qmd) - Beginner-friendly intro to `{ellmer}`
-   [**Advanced Clinical Reporting with officer & flextable**](workshops/clinical-reporting/officer-flextable.qmd) - Professional Word reports
-   [**Introduction to Building R Packages**](workshops/development-validation/building-r-packages.qmd) - Create your first package
-   [**From Data to Insights with {teal}**](workshops/specialized/teal-framework.qmd) - Interactive clinical trial apps

### Key Presentations

-   **GSK's Journey to Open Source** - 50%+ R code adoption story
-   **GenAI in Production** - Moving beyond prototypes in pharma
-   **Mosaic: ARS-Driven TFL Automation** - CDISC standards implementation
-   **LLM-Powered {gtsummary}** - QC-ready tables in minutes

### Emerging Tools

-   `{ellmer}` - LLM integration for R
-   `{cards}` - Analysis Results Data
-   `{crane}` - Extension to `{gtsummary}`
-   `{polars}` - High-performance data frames
-   `{mcpr}` - Model Context Protocol in R

## 💻 Technologies Used

-   [**Quarto**](https://quarto.org) - Publishing system
-   **GitHub Pages** - Hosting
-   **GitHub Actions** - Automated deployment
-   **Custom CSS** - R blue accent color (`#276DC2`)

## 📝 About This Project

This repository was created to document and share knowledge from the R/Pharma 2025 conference. It serves as a comprehensive resource for:

-   🎓 **Conference attendees** reviewing materials
-   🔍 **Researchers** exploring R solutions for pharma
-   💼 **Hiring managers** assessing industry trends
-   🚀 **Developers** discovering tools and best practices

## 👤 Author

**Szymon Myrta**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/myrta/) [![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat-square&logo=github&logoColor=white)](https://github.com/ACTN3) [![ORCID](https://img.shields.io/badge/ORCID-A6CE39?style=flat-square&logo=orcid&logoColor=white)](https://orcid.org/0000-0003-1714-6105)

## 🤝 Contributing

Found an error or have suggestions? Contributions are welcome!

1.  Fork the repository
2.  Create a feature branch (`git checkout -b feature/improvement`)
3.  Commit your changes (`git commit -m 'Add improvement'`)
4.  Push to the branch (`git push origin feature/improvement`)
5.  Open a Pull Request

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

-   R/Pharma 2025 conference organizers and speakers
-   All workshop instructors who shared their expertise
-   The open-source R community
-   Pharmaverse initiative

## 📞 Contact

For questions or feedback: - Open an [issue](https://github.com/ACTN3Bioinformatics/R-Pharma-2025-Workshops/issues) - Connect on [LinkedIn](https://www.linkedin.com/in/myrta/)

------------------------------------------------------------------------

**⭐ If you find this repository useful, please consider giving it a star!**

*Last updated: November 2025*