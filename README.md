# Google-Earth-Engine-Singapore-Landuse-APP
This is an app for the Singapore land use classification.
https://houweitao3.users.earthengine.app/view/jfjfjfj

![图片](https://user-images.githubusercontent.com/76504267/214070041-728c7397-4a94-4e88-82df-179ffca2fe34.png)




This app is based on Sentinel(Level 2A) images combined with digital elevation data. Using MODIS Land Cover Type Yearly Global 500m as the training set (training area in Singapore and Kuala Lumpur, number of total points: 100000), using random forest (number of trees: 80) to classify land use in Singapore (30 meters pixel resolution). The overall classification accuracy is 0.77, and the kappa is 0.57.

The classification results are shown in the map panel. The map panel shows the chart relative variable importance of the result (click on the top left corner of the figure to see the complete information). Users can download the variable importance chart in .csv by clicking on the top-right of the plot.

If you want to download the classification result, you can click "Export to Google Drive" (source code required) or click "download" to download directly to the local area (there is a possibility of failure).

If you need the source code or query some details about the source code, please contact the developer(E0950301@u.nus.edu). Or you can find it by watching the network traffic to your web browser.

The tool will derive and reduces the Sentinel image collection by calculating the median of all values at each pixel across the stack of all matching bands between the selected dates(The data is available after 2017-03-28).

**Reminder：In here just exhibit an example(or prototype). It still has many challenges to address if you want to apply it to scientific research.**
