# Overview

A file and folder structure containing the data analysis project/paper done with R/Quarto/Github by Irene Cavros and Chris Okitondo.

# Pre-requisites

This is a data analysis project using R, Quarto, Github and a reference manager that can handle bibtex. It is also assumed that you have a word processor installed (e.g. MS Word or [LibreOffice](https://www.libreoffice.org/)). You need that software stack to make use of this template.

# Structure

-   All data is found under the subfolders inside the `data` folder.
-   All code is found in the `code` folder or subfolders.
-   All results (figures, tables, computed values) are in the `results` folder or subfolders.
-   All products (manuscripts, supplements, etc.) are located in the `products` subfolders.
-   See the various `readme.md` files in those folders for some more information.

# Content

-   The untouched raw dataset can be found in the `raw_data` folder.
-   The `processing_code` folder contains several files that load the raw data, perform a bit of cleaning, and save the result in the `processed_data` folder.
-   The `analysis_code` folder contains several files that load the processed data, do an exploratory analysis, and fit models. These files produce figures and some numeric output (tables), which are saved to the `results` folder.
-   The `products` folder contains bibtex\` and CSL style files for references. Those files are used by the example manuscript and slides.
-   The `manuscript` folder contains our report written as Quarto file.

# Getting started

This is a Github repository. The best way to get it and start using it is [by following these steps.](https://help.github.com/en/articles/creating-a-repository-from-a-template)

**Once you get the repository, you can check out the analysis by executing code in order. First run the processing code, which will produce the processed data from our raw data. Then run the analysis scripts, which will take the processed data and produce some results. Then you can run the manuscript file, which pulls in the generated results and displays them.**
