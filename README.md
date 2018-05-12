# Big Data MATALAB Import and Plot Workflow

Version: MATLAB 2018a

Requirements: Download this MATLAB live script .mlx file and run. It creates the necessary big data and plots.  You will need a access to MATLAB's Parallel Computing Toolbox.

A MATLAB live script that shows a workflow to import mulitple .txt (can be editted to any file type) big data files of the same format and create visualizations (plots) for each case. For all plots, this script prints (creates) .png image files in their associate folders.

Workflow steps:

1. Initialize - Clear workspace and command window.
2. Generate some Big Data - Create big data (sine waves and sine wave noise).
3. Preprocessing - Read folder directory metadata by [datastore](https://www.mathworks.com/help/matlab/ref/datastore.html?s_tid=srchtitle) (tabularTextDatastore) for .txt files (edit to other file types).
5. Importing Tall Arrays and Saving - Create [tall arrays](https://www.mathworks.com/help/matlab/ref/tall.html?searchHighlight=tall%20array&s_tid=doc_srchtitle) for efficiently handling big data, and save as .mat files as the original .txt file names.
5. Postprocessing - Create new columns in the tall data array, such as a column minus a column for a delta difference.
6. Visualization - Create plots. Plot and save figure images in their associate case folders for reference and easy sharability.

(<img src="https://github.com/Henri93/PhillyTrees/blob/master/phillyarea.png" height="300" width="400">)
(<img src="big-data-matlab-import-and-plot-workflow/Clip.png">)


7. Appendix - additional plots for the live script.
