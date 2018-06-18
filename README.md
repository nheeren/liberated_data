# Liberated data

:heart: *This repo is under development. Feedback and pull requests, especially on the requirements, are very much appreciated.*

## Objective

This repository is a collection of data that had to be manually liberated from their publication. 

Unfortunately, it is still common practice that data in scientific publications is either entirely undocumented or only partly made available, e. g. baked into figures. It has become an essential skill of scientists to extract data from publications. The idea of this repository is to collect all the datasets that have been manually extracted and make them publicly available.

NB: The Journal of Industrial Ecology will soon adopt minimum requirements for data transparency. Among others the background data for figures will have to be provided by the authors [Hertwich et al. 2018]. 

## Requirements

For a Pull Request, please provide the following elements with your contribution. Each publication is kept in a separate folder, named after the first author and year, e.g. Einstein1905. Each folder contains the following elements. Please see the [Chastas et al. 2016](Chastas2016) for a template.

### Documentation

A markdown file with the same name as the folder, including the following elements: 

1. Authors as heading 1
2. Figure(s) number as heading 2
3. Full citation, including the DOI.
4. The image source, e.g. screenshot
5. Tool used to extract the data, e.g. [WebPlotDigitizer](https://apps.automeris.io/wpd/) v4.1. Please include the version number. 
6. Contents of the folder, minimum content should be
   - The project file of the extraction software. This could also be a PDF file with measurements plus an Excel file with unit conversions.
   - CSV file with the raw data. This file should be formatted in a way that the figure could be reproduced effortlessly.
7. Description of the necessary steps to produce the data from the original source
8. Further comments

### Project files

The project files of the software that was used for extracting the data. This could also be a PDF file with measurements plus an Excel file with unit conversions. This project is intended to be tool-agnostic, but please try to keep the data as reproducible as possible. 

### Data file

The final CSV file with the raw data. This file should be formatted in a way that the original figure / data can be reproduced effortlessly with any software, e.g. as Excel. Consider adding a serial ID column for easier referencing.

Finally add the data contribution to [overview.md](overview.md) in alphabetical order.

## Resources

- [WebPlotDigitizer](https://apps.automeris.io/wpd/) (WPD) an excellent tool that provides a number of utilities to manually and automatically extract data from plots and figures
- Hertwich, E., N. Heeren, B. Kuczenski, G. Majeau-Bettez, R.J. Myers, S. Pauliuk, K. Stadler, and R. Lifset. 2018. Nullius in Verba1: Advancing Data Transparency in Industrial Ecology. Journal of Industrial Ecology 22(1): 6–17. http://doi.wiley.com/10.1111/jiec.12738.

## TODO

- [ ] Provide or link to a tutorial on data extraction

