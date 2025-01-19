# PCR-and-PLS-Analysis-on-the-Dataset
This project, developed in R, explores Principal Component Regression (PCR) and Partial Least Squares (PLS) Regression as methodologies for analyzing the factors influencing graduation rates (Grad.Rate) in U.S. colleges and universities. The analysis is based on the College dataset from the ISLR2 package, which provides comprehensive data on various characteristics of higher education institutions.

# Instructions to Run the Quarto (.qmd) File

Follow these steps to run the provided .qmd file and reproduce the analysis. If you do not wish to run the file, you can refer to the accompanying PDF file, which contains the results and R code from the .qmd file.

1. Install Quarto
   
Make sure Quarto is installed on your system. Quarto is required to render .qmd files.

Download and install Quarto from the official website: https://quarto.org/.

2. Install R and RStudio
   
Ensure you have R and RStudio installed, as the .qmd file uses R for the analysis.

Download R: https://cran.r-project.org/

Download RStudio: https://posit.co/download/rstudio-desktop/

3. Install Required R Packages
   
Before running the file, install the necessary R packages by opening RStudio and running the following commands:

install.packages("ISLR2")

install.packages("dplyr")

install.packages("tidyr")

install.packages("pls")

4. Open the .qmd File in RStudio
   
Launch RStudio.

Navigate to the location of the .qmd file.

Open the .qmd file by clicking on it or using File > Open File.

5. Render the File
   
To render the .qmd file into your desired format (e.g., .html, .pdf, .docx):

Click the Render button in RStudio’s toolbar (usually in the top right corner of the file editor).

Alternatively, run the following command in the RStudio Console:

quarto::quarto_render("filename.qmd")

Replace filename.qmd with the actual name of the file.

6. View the Output
   
After rendering, the output file (e.g., .html, .pdf, or .docx) will appear in the same directory as the .qmd file.

Open the output file in your preferred application to view the analysis.

7. Refer to the PDF File (If Not Running the .qmd File)
   
If you prefer not to run the .qmd file, the accompanying PDF file contains all the results, visualizations, and R code from the .qmd file. This provides a comprehensive 

view of the project without needing to set up or run anything.

8. Troubleshooting
   
If you encounter any issues:

Verify that all required packages are installed.

Ensure you are running the latest versions of Quarto, R, and RStudio.

Check for errors in the console during the rendering process.
