---
output:
  pdf_document: default
  html_document: default
---
# Target population
Graduate students that are from different backgrounds and have entered the Neuromodulation/Neuroscience/biomedical engineering program

# Course Description
Biomedical data includes a diverse range of data types from patient data from national registeries, to biomarker data, to genetic and sequence data, to electrophysiological recordings from human or animal models, to simulations; usually covering multiple spatio-temporal scales. These data are usually high dimensional, noisy and fragmented. Handling such data is challenging and understanding it is the very important first step in a data-driven approach to build predictive models. This course introduces techniques to analyze biomedical data using programing languages Python and R. The focus of the course is to integrate reproducible research principles such as well-documented modular coding, correctness of procedure, and interpretability of results and presentation of outcomes of the analysis.

# Learning Outcomes
- understand complications related to using and analyzing biomedical data; with a focus in high dimensional data
- write well written, well documented modular code
- manipulate, clean and filter data and organize data properly
- discriminate between interpretable and black box models and correctly setup validated statistical models
- generate publication quality presentation of outcomes and effectively communicate technical content
- productive collaborative work in a diverse team

# Ideas for course syllabus
Programming

- Intro to Python
- Data cleaning/wrangling - tidy data
- From Data Exploration to Publication-Quality Figures
- scientific computing skills: version control and GitHub; documentation; modular coding
- making a reproducible scientific product: software to document pipeline

Quantitative methods

- best practices with high dimensional biomedical data
- dimensionality reduction, visualization and signal feature analysis
- Finding low-dimensional structure in large-scale
- time series analysis
- statistical learning framework
  - what is p-hacking and how to avoid it
- predictive-analytic models: Choosing the Best Model
  - AIC/BIC
- Project wok


# Evaluation
- Project based; small groups (O:3)
  - students will make a project plan that includes scope, significance, deliverables and milestones; overall the projects should have several phases
      - phase 1: defining the project, deciding the data, roles, etc.(including a code repo from a predefined list)
      - phase 2: code
        deliverables:
        - successful contribution to code repo (merged pull request)
        - proper documentation
        - demo/tutorial notebook
        - presentation + live demo
        - update to either CRAN or PYPi
      - phase 3: analysis
        deliverables:
        - conference report with publication quality figures
        - notebook to reproduce each of the quantitative results
        - presentation
        - results to be deposited in an open access repository
  - evaluation: the progress is evaluated at the end of each phase and the team will be graded for meeting the above deliverables and a clear and concise progress report.
