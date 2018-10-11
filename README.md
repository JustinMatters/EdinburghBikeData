# EdinburghBikeData
Python notebook tidying and visualising the Edinburgh Council Open Data for Bike Travel

Please note that Bike_Dataframe.zip unpacks to quite a large file and if you are going to run the entire workbook you don't need to download it since the workbook generates it part way through. If you do download it, you can avoid running cells 2 to 14 by simply unpacking the csv it contains and creating and running a cell containing:

bike_df = pd.read_csv("Bike_Dataframe.csv", error_bad_lines=False)

