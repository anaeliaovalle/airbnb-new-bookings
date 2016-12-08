# Predict New User Bookings on Airbnb
Where will a new guest book their first travel experience? Let's find out using D-D-DATA MINING!

This group consists of 3 awesome students from the University of San Francisco:
Anaelia Ovalle, Michael Liston, and Brent Rucker

Link to the competition: https://www.kaggle.com/c/airbnb-recruiting-new-user-bookings

This project was done using jupyter notebooks and is organized in the following ways:

- Our team was interested in comparing different method of imputation and balancing classes, therefore we have several notebooks that run different ways of doing such. This includes:
  - airbnb_original : data analysis run on the original dataset
  - airbnb_original_ageBinned: data analysis run on dataset with the age predictor binned as 18-25,25-40,40-60,60-90
  - airbnb_noNDF: data analysis run without overrepresented class NDF. Taken from response variable 'country_destination'
  - airbnb_noAgeNA: data analysis run without NA values in age predictor
  - airbnb_noNDF_noageNA_upsample: data analysis run without NA values in age predictor AND without NDF class. This file also contains an upsampling method. The top models were re-run using the upsampled training set.

- Attached is an excel spreadsheet providing the accuracy,recall, and precision for each model

- Sample tree visualization file : tree.png

**It is suggested to observe airbnb_noNDF_noageNA_upsample as this contains all relevant output
