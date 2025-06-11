This ImageJ macro helps process Fluorescence Recovery After Photobleaching (FRAP) time series data from Leica microscopes on single cells. Specifically it is useful for when the tracked photobleached object may move throughout the postbleach period such as biomolecular condensates. It's main function is to:

1. Read metadata of images for timeline
2. Concatenate pre and post bleach series together,
3. Align for XY drift if needed
4. Allow the user to select a region for background, segment the cell body for reference region, and manually set ROIs to track bleach region.
5. The output is a csv file with these columns in a format suitable for use in EasyFrap program. And the concatenated image stack with overlay for each region. 

For any issues or further customization, feel free to modify the code as needed.
