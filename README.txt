This project was done using jupyter notebooks and is organized in the following ways:

- Our team was interested in comparing different method of imputation and balancing classes, therefore we have several notebooks that run different ways of doing such. This includes:
  1) airbnb_original : data analysis run on the original dataset
  2) airbnb_original_ageBinned: data analysis run on dataset with the age predictor binned as 18-25,25-40,40-60,60-90
  3) airbnb_noNDF: data analysis run without overrepresented class NDF. Taken from response variable 'country_destination'
  4) airbnb_noAgeNA: data analysis run without NA values in age predictor
  5) airbnb_noNDF_noageNA_upsample: data analysis run without NA values in age predictor AND without NDF class. This file also contains an upsampling method. The top models were re-run using the upsampled training set.

- Attached is an excel spreadsheet providing the accuracy,recall, and precision for each model

- Sample tree visualization file : tree.png

**It is suggested to observe airbnb_noNDF_noageNA_upsample as this contains all relevant output
