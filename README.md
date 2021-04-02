# Daily Rainfall Prediction Model

This project models observed daily rainfall data over NSW, Australia. Specifically it employs building and deploying ensemble machine learning models in the cloud, in order to forecast future daily rainfall amount in Australia.

## Overview

The rainfall data is collected from daily rainfall from year 1889 to year 2014 in New South Wales, Australia (approximately 12 GB). This dataset is also hosted in [figshare](https://figshare.com/articles/dataset/Daily_rainfall_over_NSW_Australia/14096681) and we can use the `figshareAPI` in order to download the data locally.

The features of the data set are outputs from different climate models and the response is the amount of actual rainfall observation.

## Objective

There are total of four objectives for this project:

1. Acquire the data from website using API into analysis friendly, machine learning efficient format.

2. Transfer the formated data into cloud, and set up the infrastructure for machine learning model.

3. Build distributed infrastructure in cloud, for example EMR-spark, to perform machine learning in cloud.

4. Deploy our machine learning model in cloud so our customer can run the model in could.

## Dependencies

TBA

## Contributors

Members of the team and their Github.com names are shown below: 

| Name                | Github.com name |
|---------------------|-----------------|
| Deepak Sidhu | @deepaksidhu      |
|  Zhenrui Yu   | @yzr1996    |
| Bruhat Musunuru      | @BruhatM       |
| Jiacheng Wang  | @wangjc640  |

## Credits

The data set in use is taken from from [figshareAPI](https://doi.org/10.6084/m9.figshare.14096681.v3), it was created by Tomas Beuzen.

The preprocess, including download and process data, is demonstrated by [this example](https://github.ubc.ca/MDS-2020-21/DSCI_525_web-cloud-comp_students/blob/master/get_data.ipynb) by Dr.Gittu George.
 
## License

- All meterial used in this Github Repo of predicting daily rainfall in New South Wales are licensed under the [MIT License](https://github.com/git/git-scm.com/blob/main/MIT-LICENSE.txt)

- The NSW rainfall dataset is licensed under the [Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)