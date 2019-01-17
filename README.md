# ETL

1. 	Extract
	Used web scraper tool to scrape TripAdvisor and sandiegoevents.com to extract data and saved them as csv files. 

2.	Transform
	Used Jupyter Notebook and Pandas.
	Imported dependencies: pandas 
	
	2.1.	Processed File 1: events.csv
			Used pd.read_csv to read file and put it in a dataframe called events1_df.
			Dropped unwanted column "Reviews" from dataframe. 
			Renamed column "Description" to "Name"
			Removed the first 3 words in "Category" column by using the split and join functions
	
	2.2		Processed File 2: TripAdvisor.csv
			Used pd.read_csv to read file and put it in a dataframe called events2_df.
			Dropped unwanted column "# of reviews" from dataframe.
	
	2.3		Combined events1_df and events2_df into 

			
3.	Load
	Created database connection using create engine from sqlalchemy
	
	
	
