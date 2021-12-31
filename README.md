# House Price Index Project

Working Process
- Data Preparation.
  - [x] Irrelevant observation cleaning.
  - [x] Geo data combination.
  - [x] Geo data (missing coordinates) fixing by OSM and Google API.
  - [x] Save data files.
- Model Testing.
  - [x] Model testing using different strategies and default parameters (Gaussian, 2000, 14, 0.05, 15, 0.5)
    - [x] Full time period strategy.
    - [x] Rolling windows strategy.
    - [x] Cross section strategy.
    - [x] Cross section strategy (chained index).
    - [x] Resales strategy (Case-Shiller).
  - [x] Global Index construction.
    - [x] ML method(ALE).
    - [x] Imputation method (T index).
    - [x] Repeat sales method.
  - [x] Global Index quality test.
  - [ ] Local Indices construction.
    - [ ] ML method(ALE).
    - [ ] Imputation method (T index).
    - [ ] Repeat sales method.
  - [ ] Local Indices quality test.
  - [ ] Revision.
- Paper Writing.
  - [x] Introduction.
  - [x] Methodology.
  - [x] Data section.
  - [ ] Results.
  - [ ] Conclusion.
- Paper Reviewing.
