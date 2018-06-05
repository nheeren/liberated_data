# Chastas et al. 2016 

Chastas, P., T. Theodosiou, and D. Bikas. 2016. Embodied energy in residential buildings-towards the nearly zero energy building: A literature review. Building and Environment. 105: 267–282. http://dx.doi.org/10.1016/j.buildenv.2016.05.040. DOI: 10.1016/j.buildenv.2016.05.040.

## Figure 8

- Image source: High-res image from the publisher, https://www.sciencedirect.com/science/article/pii/S0360132316301986?via%3Dihub#fig8
- Tool: [WebPlotDigitizer](https://apps.automeris.io/wpd/) v4.1 (WPD)
- Dataset contains:
  - WPD JSON project file (folder [WPD_Fig8](WPD_Fig8))
  - CSV exported from WPD with manual corrections (file [Fig8.csv](Fig8.csv))
    - id: serial ID column, corresponding to figure's case study number minus one
    - red: red data column, i.e. "Embodied Energy"
    - darkgrey: dark grey data column, i.e. "Operating Energy"
- Steps:
  - Extracted only red and dark grey bars, because the light grey bar is their sum
  - Automatic "Bar Extraction" algorithm in WPD 
  - Had to correct order of data, because of many false positives in the automatic point recognition in WPD
- Comments
  - The data point names given by WPD (e.g. Bar0) are not consecutive and also redundant sometimes