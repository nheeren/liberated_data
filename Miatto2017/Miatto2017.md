# Miatto et al. 2017 

- Authors: Miatto, A., H. Schandl, T. Fishman, and H. Tanikawa
- Year: 2017 
- Title: Global Patterns and Trends for Non-Metallic Minerals used for Construction
- Journal: Journal of Industrial Ecology 21(4): 924–937
- DOI: http://doi.wiley.com/10.1111/jiec.12471

## Figure 2

- Image source: Screenshot from ca. 400% magnification (y-axis is cut of at 30000). This had a higher resolution than the files offered by the journal.
- Tool: [WebPlotDigitizer](https://apps.automeris.io/wpd/) v4.1 (WPD)
- Dataset contains:
  - WPD JSON project file (folder [WPD_Fig2](WPD_Fig2))
  - CSV exported from WPD with manual corrections (file [Fig2.csv](Fig2.csv))
    - Year: Year of datapoint as in the publication
    - Building and infrastructure
    - Roads
    - Bricks
    - Railway
- Steps:
  - Automatic "Bar Extraction" algorithm in WPD 
  - Corrected order of data, because values had to be added manually in WPD
  - Subtracted the data of the lower stack, e.g. roads minus buildings & infrastructure, to have the data series' individual value and not cumulated
- Comments
  - Yellow dataset (railway) is too small and was for very small numbers too blurry