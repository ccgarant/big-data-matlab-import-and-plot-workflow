# Big Data MATALAB Import and Plot Workflow

### Version:
MATLAB 2018a

### Getting Started: 
- See the .pdf file for a quick view
- Download and run the MATLAB live .mlx script. 

### Description:
A MATLAB live script that shows a workflow of how to handle big data.  This script shows you how to read and import files from your folder directory using datastore, create workspace variables using tall arrays, pre and post process data using tall arrays, and finally create visualizations (plots) for each case. For all plots, this script prints (creates) .png image files in their associate created folders.

### Workflow steps:

1. Initialize - Clear workspace and command window.

2. Generate some Big Data - Create big data (sine waves and sine wave noise).
<img src="https://github.com/ccgarant/big-data-matlab-import-and-plot-workflow/blob/master/Clip.png" height="500" width="600">

3. Preprocessing - Read folder directory metadata by [datastore](https://www.mathworks.com/help/matlab/ref/datastore.html?s_tid=srchtitle) (tabularTextDatastore) for .txt files (edit to other file types).

4. Importing Tall Arrays and Saving - Create [tall arrays](https://www.mathworks.com/help/matlab/ref/tall.html?searchHighlight=tall%20array&s_tid=doc_srchtitle) for efficiently handling big data, and save as .mat files as the original .txt file names.

5. Postprocessing - Create new columns in the tall data array, such as a column minus a column for a delta difference.
<img src="https://github.com/ccgarant/big-data-matlab-import-and-plot-workflow/blob/master/Delta.png" height="500" width="600">

6. Visualization - Create plots. Plot and save figure images in their associate case folders for reference and easy sharability.  Compare different test cases.
<img src="https://github.com/ccgarant/big-data-matlab-import-and-plot-workflow/blob/master/Delta%20Comparison_1.png" height="500" width="600">

7. Appendix - additional plots for the live script.

Feedback welcomed! :)




