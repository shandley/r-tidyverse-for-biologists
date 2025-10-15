# R and Tidyverse for Biology Graduate Students

A comprehensive course on data analysis using R and the tidyverse, designed specifically for biology graduate students with no prior programming experience.

## Course Overview

This course teaches modern data analysis techniques using R and the tidyverse ecosystem. All lessons are designed to run on **posit.cloud**, requiring no local installation. Each lesson uses small, biology-relevant datasets and includes hands-on exercises and homework assignments.

## Prerequisites

- No programming experience required
- Basic understanding of biological concepts
- Access to posit.cloud (free tier is sufficient)

## Learning Objectives

By the end of this course, students will be able to:

- Write reproducible data analysis workflows using R and RMarkdown
- Import, clean, transform, and visualize biological data
- Perform statistical analyses using modern tidyverse-compatible packages
- Apply machine learning techniques to biological datasets
- Conduct complete analyses of real-world biological data including RNA-seq, microbiome, and metagenomic datasets

## Course Structure

The course is organized into **5 blocks** with **18 lessons**:

### Block 1: Core Foundations (Lessons 1-6)
Essential R and tidyverse skills for data manipulation and visualization.

**Lesson 1: Introduction to R and RMarkdown**
- R basics: vectors, functions, data types
- Introduction to RMarkdown for reproducible reports
- Running code chunks and creating formatted documents

**Lesson 2: Data Import and Exploration**
- Loading the tidyverse
- Reading CSV files with `readr`
- Initial data exploration with `glimpse()`, `summary()`, and basic plots
- Understanding tibbles

**Lesson 3: Data Transformation with dplyr**
- Filtering rows with `filter()`
- Selecting columns with `select()`
- Creating new variables with `mutate()`
- Sorting data with `arrange()`
- The pipe operator `%>%` for chaining operations

**Lesson 4: Grouping and Summarizing Data**
- Grouping data with `group_by()`
- Calculating summary statistics with `summarise()`
- Counting observations with `count()`
- Applying transformations by group

**Lesson 5: Data Visualization with ggplot2**
- Grammar of Graphics concept
- Creating histograms, boxplots, and scatter plots
- Customizing plots with themes and colors
- Faceting for multi-panel plots

**Lesson 6: Joining and Reshaping Data**
- Combining datasets with joins: `left_join()`, `inner_join()`, `full_join()`
- Reshaping data with `pivot_longer()` and `pivot_wider()`
- Tidy data principles

### Block 2: Essential Tools (Lessons 7-9)
Additional tidyverse packages and best practices for reproducible research.

**Lesson 7: Text Data with stringr**
- String manipulation: `str_detect()`, `str_extract()`, `str_replace()`
- Regular expressions for pattern matching
- Working with gene IDs and DNA sequences
- Parsing biological data formats

**Lesson 8: Time Series with lubridate**
- Parsing dates and times
- Date arithmetic and intervals
- Working with longitudinal biological data
- Time-based grouping and visualization

**Lesson 9: Reproducible Research**
- R Projects for organization
- The `here` package for file paths
- Managing dependencies with `renv`
- Creating parameterized RMarkdown reports
- Best practices for reproducible analyses

### Block 3: Statistics and Modeling (Lessons 10-11)
Statistical analysis using tidyverse-compatible approaches.

**Lesson 10: Statistical Testing**
- t-tests, ANOVA, and non-parametric tests with `rstatix`
- Multiple testing correction
- Effect sizes and confidence intervals
- Tidying statistical results with `broom`

**Lesson 11: Linear Models and GLMs**
- Simple and multiple linear regression
- Model diagnostics and assumptions
- Logistic regression for binary outcomes
- Poisson regression for count data
- Working with model objects in a tidy workflow

### Block 4: Advanced Methods (Lessons 12-15)
Advanced tidyverse techniques and machine learning.

**Lesson 12: Functional Programming with purrr**
- The `map()` family of functions
- Iterating over multiple inputs with `map2()` and `pmap()`
- Error handling with `safely()` and `possibly()`
- Working with list columns

**Lesson 13: Advanced tidyr with Nested Data**
- Creating nested data with `nest()`
- Working with list columns containing models and plots
- Unnesting results with `unnest()`
- Combining nesting with `purrr` for powerful workflows

**Lesson 14: Machine Learning with tidymodels**
- The `tidymodels` workflow
- Data splitting and cross-validation
- Training classification and regression models
- Hyperparameter tuning
- Model evaluation and comparison

**Lesson 15: Complete Analysis Case Study**
- Antibiotic resistance analysis in *E. coli*
- Integrating all skills learned: import, transform, visualize, test, and report
- Complete workflow from raw data to publication-ready results

### Block 5: Domain-Specific Applications (Lessons 16-18)
Real-world biological data analysis workflows.

**Lesson 16: RNA-seq Analysis**
- Gene expression data structure
- Principal Component Analysis (PCA)
- Differential expression analysis
- Volcano plots and heatmaps
- Gene ontology enrichment

**Lesson 17: Microbiome Analysis (16S Amplicon)**
- Working with taxonomic abundance data
- Alpha diversity metrics
- Beta diversity and ordination
- Taxonomic composition plots
- Differential abundance testing

**Lesson 18: Metagenomics Analysis (Shotgun)**
- Functional annotation data
- Pathway analysis
- Antibiotic resistance gene profiling
- Comparing functional profiles across samples
- Integrating taxonomic and functional data

## How to Use This Course

### For Instructors

Each lesson is designed to be completed in a 2-3 hour session including:
- 45-60 minutes of instruction/demonstration
- 60-90 minutes of hands-on practice
- Homework exercises for additional practice

Lessons build on each other sequentially. We recommend following the order presented, though Blocks 4 and 5 can be partially customized based on student interests.

### For Students

1. **Open the lesson** in posit.cloud
2. **Read through the content** and run code chunks as you go
3. **Complete the practice exercises** embedded in each lesson
4. **Attempt the homework** to reinforce learning
5. **Experiment** with the code - modify parameters and see what happens!

### Getting Started with posit.cloud

1. Create a free account at [posit.cloud](https://posit.cloud)
2. Create a new project
3. Upload the lesson RMarkdown file
4. Click "Knit" to render the document
5. Work through the content interactively

## Required R Packages

All lessons use tidyverse-compatible packages. The most frequently used packages are:

**Core tidyverse:**
- `dplyr` - data transformation
- `ggplot2` - data visualization
- `tidyr` - data reshaping
- `readr` - data import
- `purrr` - functional programming
- `stringr` - string manipulation
- `lubridate` - date/time handling

**Statistics and modeling:**
- `rstatix` - tidy statistical tests
- `broom` - tidy model outputs
- `tidymodels` - machine learning framework

**Reproducibility:**
- `here` - file path management
- `renv` - dependency management
- `rmarkdown` - reproducible reports

**Domain-specific:**
- Dataset-specific packages are introduced in relevant lessons

## Datasets

All datasets are small enough to work efficiently on posit.cloud's free tier. Datasets include:

- `palmerpenguins::penguins` - penguin morphology (Lessons 1-6)
- Simulated biological datasets for specific concepts
- Real-world subsampled datasets for case studies (RNA-seq, microbiome, metagenomics)

## Philosophy

This course emphasizes:

1. **Tidyverse first**: Modern R syntax using tidyverse packages over base R when possible
2. **Reproducibility**: All analyses should be reproducible from RMarkdown documents
3. **Real biology**: Examples and datasets from actual biological research
4. **Practical skills**: Focus on workflows students will use in their research
5. **Progressive complexity**: Building skills gradually from foundations to advanced applications

## Additional Resources

- [R for Data Science](https://r4ds.had.co.nz/) - Comprehensive tidyverse textbook
- [RStudio Education](https://education.rstudio.com/) - Learning resources
- [Tidy Tuesday](https://github.com/rfordatascience/tidytuesday) - Weekly data practice
- [posit.cloud Primers](https://posit.cloud/learn/primers) - Interactive tutorials

## Contributing

Suggestions for improvements are welcome! Please consider:
- Additional biological datasets
- New case study topics
- Clarifications to existing lessons
- Additional practice exercises

## License

These materials are provided for educational purposes. Feel free to adapt and use in your own courses with attribution.

---

**Course Developer**: Designed for biology graduate students learning R and the tidyverse
**Platform**: posit.cloud
**Level**: Beginner to intermediate
**Time**: 18 lessons × 2-3 hours each = ~40-50 hours total
