# project

The final project is a work of exposition/tutorial in which you explore a topic related to machine learning for causal inference both analytically and computationally. Discuss the foundations for this work in statistics or related fields. Then, choose and focus on some aspect of how this work has developed, competing methodologies or debates with associated benefits and drawbacks, and directions for future research. Demonstrate these ideas with a computational example (i.e. write code). The deliverable is a 5 page paper that should include focused code snippets (if appropriate) and key output as well as a script or notebook and related data that can be run all the way through after setting the working directory. For example, you can write an Rmd or Jupyter notebook where only the most important code and output for understanding your point is shown in the pdf output (there should not be extraneous code in the report). The reader of your report should come away with a good understanding of the strengths and drawbacks of the method/theme as well as how to use them effectively. The class demonstration is a good place to start for this project, but you are not required to have your project be an extension of your class demonstration.

You will be graded not only on the accuracy of your analysis, but also on the clarity of your exposition, which includes notation, typesetting (equation alignment, exceeding margins), grammar, figures, tables, etc. All code should be reproducible--please provide any supporting files necessary with your submission. The more difficult it is to read your work, the fewer points you will receive. Follow a coding style guide (e.g. https://style.tidyverse.org/ and https://peps.python.org/pep-0008/) and stick to it. The expectation is for polished work.

To create a polished document, I suggest using Quarto, LaTeX, RMarkdown or a similar markup language. Organize your files clearly so I can immediately find relevant files (a README with a Table of Contents can also help). You should use subdirectories and packages as appropriate for your project, e.g.:
```
data/
├─ lalonde.csv
├─ nsw_rct.csv
figures/
├─ rmse.pdf
├─ runtime.pdf
simulation_output/
├─ simulation_results.csv
simulation_package/
├─ data_generator.py
├─ estimator.py
├─ evaluator.py
├─ __init__.py
pyproject.toml
run_analysis.R
run_simulations.py
writeup.pdf
writeup.tex
```

Alternatively, students may submit original work, such as a research proposal for a project they are working on. This option is available with instructor permission only.

## Expectations

### Content & Analysis (35 points)
- *Excellent (32-35)*: Demonstrates deep understanding of chosen causal ML topic. Clear discussion of foundations, competing approaches, and trade-offs. Insightful analysis of strengths/weaknesses. Thoughtful directions for future research.
- *Good (26-31)*: Solid understanding with adequate coverage of foundations and methods. Some analysis of trade-offs and limitations. Basic future directions identified.
- *Satisfactory (21-25)*: Basic understanding evident but shallow treatment. Limited discussion of competing approaches or trade-offs. Weak or missing future research directions.
- *Poor (0-20)*: Fundamental misunderstandings or inadequate coverage of topic. No clear analysis of methods or their limitations.
### Technical Implementation (30 points)
- *Excellent (27-30)*: Code runs flawlessly, follows style guide, well-documented. Computational example clearly demonstrates key concepts. All files organized and reproducible.
- *Good (24-26)*: Code mostly works with minor issues. Generally follows style conventions. Example adequately demonstrates concepts. Mostly reproducible.
- *Satisfactory (19-23)*: Code has some issues but generally functional. Basic organization present. Example somewhat relevant but unclear connection to main points.
- *Poor (0-18)*: Code doesn't run, poorly organized, or irreproducible. Example fails to demonstrate key concepts or is missing entirely.
### Writing & Exposition (25 points)
- *Excellent (23-25)*: Clear, engaging writing with proper notation and formatting. Excellent figures/tables. Reader gains strong understanding of when/how to use methods.
- *Good (20-22)*: Generally clear writing with minor issues. Good use of notation and figures. Reader understands main points and applications.
- *Satisfactory (16-19)*: Adequate writing but some clarity issues. Basic notation and figures present. Limited guidance on practical application.
- *Poor (0-15)*: Poor writing quality, notation errors, or formatting issues significantly impede understanding.
### Organization & Presentation (10 points)
- *Excellent (9-10)*: Professional presentation with clear file structure, appropriate length (5 pages), excellent typesetting.
- *Good (7-8)*: Well-organized with minor presentation issues. Appropriate length and generally good formatting.
- *Satisfactory (5-6)*: Basic organization present but some structural issues. Length appropriate but formatting inconsistent.
- *Poor (0-4)*: Poor organization, inappropriate length, or significant formatting problems.
