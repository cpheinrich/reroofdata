# Reroof Data
Dataset for paper: Roof age determination for the automated site selection of rooftop solar



## About the data

Training, validation and image data is available for download

- https://drive.google.com/open?id=1EO0PZclNhakke8PjXuE2rpSyzN0vGndc

The subdirectory for each property contains 7 images from the years 2012-2018. Each subdirectory also contains a `metadata.json` file, and the value for key `new_roof_year` labels the first year of the new roof. So for example if this has value 2015, then the roof was replaced between the 2014 and 2015 images. If this value is null, it means the roof was not replaced in the 2012-2018 range. 

We also include a .csv of all the reroof data for commercial properties in Los Angeles at `la_commercial_reroofs.csv`.

