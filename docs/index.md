---
layout: default
title: R and Tidyverse for Biology Graduate Students
---

# R and Tidyverse for Biology Graduate Students

A comprehensive course on data analysis using R and the tidyverse, designed for biology graduate students with no prior programming experience.

**Platform:** [posit.cloud](https://posit.cloud) | **Level:** Beginner to Intermediate | **Duration:** ~40-50 hours

[📚 View Full Course Documentation](https://github.com/shandley/r-tidyverse-for-biologists/blob/main/README.md) | [💬 Join Discussions](https://github.com/shandley/r-tidyverse-for-biologists/discussions) | [⭐ Star on GitHub](https://github.com/shandley/r-tidyverse-for-biologists)

---

## 📖 Course Lessons

### Block 1: Core Foundations
**Essential R and tidyverse skills for data manipulation and visualization**

1. [Introduction to R and RMarkdown](https://github.com/shandley/r-tidyverse-for-biologists/blob/main/lesson01_intro_to_R_and_RMarkdown.Rmd)
   - R basics, vectors, functions, RMarkdown syntax

2. [Data Import and Exploration](https://github.com/shandley/r-tidyverse-for-biologists/blob/main/lesson02_data_import_exploration.Rmd)
   - Loading tidyverse, reading CSV files, initial exploration

3. [Data Transformation with dplyr](https://github.com/shandley/r-tidyverse-for-biologists/blob/main/lesson03_data_transformation.Rmd)
   - filter(), select(), mutate(), arrange(), pipe operator

4. [Grouping and Summarizing Data](https://github.com/shandley/r-tidyverse-for-biologists/blob/main/lesson04_grouping_summarizing.Rmd)
   - group_by(), summarise(), count(), group transformations

5. [Data Visualization with ggplot2](https://github.com/shandley/r-tidyverse-for-biologists/blob/main/lesson05_data_visualization.Rmd)
   - Grammar of Graphics, plots, themes, faceting

6. [Joining and Reshaping Data](https://github.com/shandley/r-tidyverse-for-biologists/blob/main/lesson06_joining_reshaping.Rmd)
   - Joins, pivot_longer(), pivot_wider(), tidy data

---

### Block 2: Essential Tools
**Additional tidyverse packages and reproducible research practices**

7. [Text Data with stringr](https://github.com/shandley/r-tidyverse-for-biologists/blob/main/lesson07_stringr_text_data.Rmd)
   - String manipulation, regex, gene IDs, DNA sequences

8. [Time Series with lubridate](https://github.com/shandley/r-tidyverse-for-biologists/blob/main/lesson08_lubridate_time_series.Rmd)
   - Date/time parsing, date arithmetic, longitudinal data

9. [Reproducible Research](https://github.com/shandley/r-tidyverse-for-biologists/blob/main/lesson09_reproducible_research.Rmd)
   - R Projects, here package, renv, parameterized reports

---

### Block 3: Statistics and Modeling
**Statistical analysis using tidyverse-compatible approaches**

10. [Statistical Testing](https://github.com/shandley/r-tidyverse-for-biologists/blob/main/lesson10_statistical_testing.Rmd)
    - t-tests, ANOVA, non-parametric tests, multiple testing correction

11. [Linear Models and GLMs](https://github.com/shandley/r-tidyverse-for-biologists/blob/main/lesson11_linear_models_glms.Rmd)
    - Linear regression, logistic regression, Poisson regression

---

### Block 4: Advanced Methods
**Advanced tidyverse techniques and machine learning**

12. [Functional Programming with purrr](https://github.com/shandley/r-tidyverse-for-biologists/blob/main/lesson12_purrr_functional_programming.Rmd)
    - map() family, iteration, error handling, list columns

13. [Advanced tidyr with Nested Data](https://github.com/shandley/r-tidyverse-for-biologists/blob/main/lesson13_advanced_tidyr_nested.Rmd)
    - nest(), unnest(), list columns with models and plots

14. [Machine Learning with tidymodels](https://github.com/shandley/r-tidyverse-for-biologists/blob/main/lesson14_machine_learning_tidymodels.Rmd)
    - tidymodels workflow, cross-validation, hyperparameter tuning

15. [Complete Analysis Case Study](https://github.com/shandley/r-tidyverse-for-biologists/blob/main/lesson15_case_study.Rmd)
    - Antibiotic resistance in *E. coli* - integrating all skills

---

### Block 5: Domain-Specific Applications
**Real-world biological data analysis workflows**

16. [RNA-seq Analysis](https://github.com/shandley/r-tidyverse-for-biologists/blob/main/lesson16_rnaseq_case_study.Rmd)
    - Gene expression, PCA, differential expression, volcano plots

17. [Microbiome Analysis (16S Amplicon)](https://github.com/shandley/r-tidyverse-for-biologists/blob/main/lesson17_microbiome_case_study.Rmd)
    - Alpha/beta diversity, taxonomic composition, differential abundance

18. [Metagenomics Analysis (Shotgun)](https://github.com/shandley/r-tidyverse-for-biologists/blob/main/lesson18_metagenomics_case_study.Rmd)
    - Functional annotation, pathway analysis, ARG profiling

---

## 🚀 Getting Started

### For Students

1. **Create a free account** at [posit.cloud](https://posit.cloud)
2. **Download a lesson** (click the lesson link above, then "Raw", then save)
3. **Upload to posit.cloud** in your project
4. **Click "Knit"** to render the RMarkdown document
5. **Work through interactively** - run code chunks and complete exercises

### For Instructors

Each lesson is designed for a 2-3 hour session:
- 45-60 min instruction
- 60-90 min hands-on practice
- Homework for additional practice

Lessons build sequentially - follow the order presented for best results.

---

## 📦 Required Packages

**Core tidyverse:** dplyr, ggplot2, tidyr, readr, purrr, stringr, lubridate

**Statistics & modeling:** rstatix, broom, tidymodels

**Reproducibility:** here, renv, rmarkdown

All packages are introduced in relevant lessons with installation instructions.

---

## 💡 Course Philosophy

1. **Tidyverse first** - Modern R syntax over base R when possible
2. **Reproducibility** - All analyses in RMarkdown documents
3. **Real biology** - Examples from actual biological research
4. **Practical skills** - Focus on workflows for real research
5. **Progressive complexity** - Build from foundations to advanced applications

---

## 🤝 Contributing

Have suggestions? Found an issue? Want to contribute a new case study?

- [Open an issue](https://github.com/shandley/r-tidyverse-for-biologists/issues)
- [Start a discussion](https://github.com/shandley/r-tidyverse-for-biologists/discussions)
- Submit a pull request

---

## 📄 License

This course is licensed under the [MIT License](https://github.com/shandley/r-tidyverse-for-biologists/blob/main/LICENSE). Feel free to use and adapt these materials with attribution.

---

## 🔗 Additional Resources

- [R for Data Science](https://r4ds.had.co.nz/) - Comprehensive tidyverse textbook
- [RStudio Education](https://education.rstudio.com/) - Learning resources
- [Tidy Tuesday](https://github.com/rfordatascience/tidytuesday) - Weekly data practice
- [posit.cloud Primers](https://posit.cloud/learn/primers) - Interactive tutorials

---

<p align="center">
  <strong>Questions? Join the <a href="https://github.com/shandley/r-tidyverse-for-biologists/discussions">Discussion</a>!</strong>
</p>

<p align="center">
  Made with 🧬 for biology graduate students learning R
</p>
