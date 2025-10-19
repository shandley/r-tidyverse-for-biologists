# R and Tidyverse for Biology Graduate Students

## Project Overview

Educational course teaching R and the tidyverse to biology graduate students with no programming experience. 18 RMarkdown lessons organized into 5 pedagogical blocks, designed to run on posit.cloud.

## Key Technical Decisions

### Tidyverse-First Approach
- Prioritize tidyverse packages over base R throughout all lessons
- Statistics: Use `rstatix` and `broom` instead of base R statistical functions
- Machine learning: Use `tidymodels` framework
- This is a deliberate pedagogical choice for consistency and modern best practices

### Platform Constraints
- All lessons must work on posit.cloud free tier
- Datasets must be small (use `palmerpenguins::penguins` or simulated data)
- No local installation required
- Avoid computationally intensive operations

### Lesson Ordering Rationale

Lessons are numbered based on pedagogical progression, not creation order:

**Block 1 (1-6):** Core tidyverse foundations must come first
**Block 2 (7-9):** Essential tools including reproducible research practices early (lesson 9)
**Block 3 (10-11):** Statistics before case studies so students have necessary tools
**Block 4 (12-15):** Advanced methods culminating in complete case study (lesson 15)
**Block 5 (16-18):** Domain-specific applications as capstone projects

This ordering ensures students have prerequisites before advanced topics.

## File Structure

```
lesson[01-18]_[topic].Rmd    # 18 sequential RMarkdown lessons
README.md                     # Complete course documentation
docs/index.md                 # GitHub Pages site
LICENSE                       # MIT License
```

## Lesson Anatomy

Each lesson follows this structure:
1. YAML frontmatter with title, author, date, output format
2. Introduction explaining concepts
3. Code examples with explanations
4. Practice exercises embedded throughout
5. Homework section at end
6. All code must be self-contained and runnable in posit.cloud

## Important Conventions

### Datasets
- Use real biological examples (gene expression, taxonomic data, clinical measurements)
- Prefer publicly available datasets (palmerpenguins, simulated data)
- Keep dataset size under 1MB for posit.cloud compatibility

### Code Style
- Use tidyverse style guide
- Always load `library(tidyverse)` at the start
- Use pipe operator `%>%` (not `|>`) for consistency
- Include comments explaining biological context, not just code mechanics

### Package Dependencies
Never assume package installation. Each lesson includes:
```r
if (!require(packagename)) install.packages("packagename")
library(packagename)
```

## GitHub Pages

The `docs/index.md` file generates the course website at https://shandley.github.io/r-tidyverse-for-biologists/

All lesson links must use full GitHub URLs:
- Correct: `https://github.com/shandley/r-tidyverse-for-biologists/blob/main/lesson01_*.Rmd`
- Incorrect: `../lesson01_*.Rmd` (will 404 on GitHub Pages)

## Target Audience

- Biology graduate students
- No programming experience
- Strong wet lab skills
- Need R for thesis research
- Interested in RNA-seq, microbiome, or metagenomics analysis

## Future Development Considerations

### Adding New Lessons
- Insert in logical pedagogical order (may require renumbering)
- Ensure prerequisites are met by earlier lessons
- Test on posit.cloud free tier before committing
- Follow established patterns for exercises and homework

### Updating Existing Lessons
- Maintain backward compatibility with posit.cloud
- Keep tidyverse-first approach
- Update package installation if dependencies change
- Test all code chunks actually run

### Potential Expansions
- Additional case studies on different biological domains
- Advanced visualization techniques
- Spatial transcriptomics or single-cell analysis
- Integration with Python (reticulate) for students who need both

## Version Information

Current version: v1.0
R version target: 4.0+
Primary packages: tidyverse, rstatix, broom, tidymodels
