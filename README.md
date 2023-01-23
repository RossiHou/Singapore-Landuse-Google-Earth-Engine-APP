# Google-Earth-Engine-Landuse-APP
This is an app for the Singapore land use classification.
https://houweitao3.users.earthengine.app/view/jfjfjfj

![123123](https://user-images.githubusercontent.com/76504267/214066611-b66d30cb-2528-4b93-be40-9288bb857857.png)



This app is based on Sentinel(Level 2A) images combined with digital elevation data. Using MODIS Land Cover Type Yearly Global 500m as the training set (training area in Singapore, number of training points: 100000), using random forest (number of trees: 80) to classify land use in Singapore (30 meters pixel resolution). The overall classification accuracy is 0.91, and the kappa is 0.85.

The classification results are shown in the map panel. The map panel shows the chart relative variable importance of the result (click on the top left corner of the figure to see the complete information). Users can download the variable importance chart in .csv by clicking on the top-right of the plot.

If you want to download the classification result, you can click "Export to Google Drive" (source code required) or click "download" to download directly to the local area (there is a possibility of failure).

If you need the source code or query some details about the source code, please contact the developer(E0950301@u.nus.edu). Or you can find it by watching the network traffic to your web browser.
