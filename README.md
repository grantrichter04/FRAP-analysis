THIS README GENERATED FROM CHATGPT 4o ON 29/05/2024


ImageJ Macro for FRAP Analysis

This ImageJ macro facilitates Fluorescence Recovery After Photobleaching (FRAP) analysis. It allows users to set various parameters, process image stacks, and generate reports based on ROI measurements. Follow the instructions below to use the macro.
Features

Pre-bleach, Bleach, and Post-bleach Image Handling: Handles different time intervals and frames for pre-bleach, bleach, and post-bleach periods.
Image Duplication and Renaming: Duplicates and renames images for easy processing.
Image Concatenation: Concatenates images based on user inputs.
Animation: Provides animation options for better visualization.
Stack Alignment: Option to align image stacks if stabilization is needed.
ROI Management: Manages Regions of Interest (ROIs) for both bleach and background areas.
Measurement and Reporting: Measures ROI properties and generates a report in CSV format.

User Input Dialog

Upon running the macro, a dialog box will prompt the user to input the following parameters:

Prebleach Time Interval
Prebleach Frames
Total Time Bleaching
First Postbleach Time Interval
First Postbleach Frames
Include Second Postbleach Time Series?
Second Postbleach Time Interval
Second Postbleach Frames
Include Third Postbleach Time Series?
Third Postbleach Time Interval
Third Postbleach Frames
Taken on Sp5?

How to Use

Set Measurements and Clear Results: The macro begins by setting measurements and clearing previous results.
Input Parameters: A dialog box will appear for the user to input the necessary bleaching parameters.
Duplicate and Rename Images: The macro will duplicate and rename images based on the opened originals.
Concatenate Images: Based on user input, the macro will concatenate the prebleach and postbleach images.
Image Processing: The macro enhances image contrast, plays animations, and optionally stabilizes the cell if needed.
ROI Handling: ROIs for bleach and background areas are created, positioned, and measured.
Generate Report: The macro generates a report of the measurements and saves it as a CSV file.
Save Files: The user is prompted to specify the directory and filename for saving the results.

Notes

Ensure that all images are correctly named (Pre, Pb1, Pb2, Pb3) before running the macro.
Verify the ROIs to avoid overlapping and ensure accurate measurements.
The macro supports different bleaching protocols (SP5 and SP8).

For any issues or further customization, feel free to modify the code as needed.
