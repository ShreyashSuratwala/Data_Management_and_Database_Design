---------------
--README file--
---------------


--IMPORTANT--
Please read thru this document before going thru the main assignment file.
There are Do's and Dont's to follow to view this assignment in it's IDEAL form.


Assignment :
	This assignment is to convert SQL formatted database to NoSQL formatted database. No changes in the Schema of SQL formated database was made to accomodate it into NoSQL formatted database.
	
	Main File
		- Assignemnt #3 - NoSQL MongoDB.ipynb

	Files associated with the assignment :
		For Sales Data :
			- salesDataSample.csv
		
		For SQL storage (Input)
			- customerTableFinal.csv
			- orderTableFinal.csv
			- productTableFinal.csv

		For NoSQL (MongoDB) storage (Output)
			- customerTableFinal.json
			- orderTableFinal.json
			- productTableFinal.json

		Data extraction (Processed to extract solution)
			- similarCustomer.csv (Contains customer similarity data)
			- popularityAllTime.csv (Contains all time products popularity)
			- popularityYr2003.csv (Contains trending products in year 2003)
			- popularityYr2004.csv (Contains trending products in year 2004)
			- popularityYr2005.csv (Contains trending products in year 2005)

		For Web-scraped data
			- poeStats.csv

		For Web-scraped storage (Solutions)
			- poeStats_tagsAssociatedClass.csv
			- poeStats_tagsAssociatedLadder.csv
			- poeStats_classNecromancer.csv
			- poeStats_classSlayer.csv
			- poeStats_classDeadeye.csv


For the ASSIGNMENT:

The entire project is contained by "Assignemnt #3 - NoSQL MongoDB.ipynb" file
The said document contains all the code required to obtain and extract the data from it's raw tabular format.
The data would be output from small pop-up windows which would prompt to save the data. The pop-up UI is designed and developed with the help if Tkinter.
For the application to progress smoothly, exit the pop-up's after they are finished processing as they would block the application to progress further if not exited from their windows.

There is a need to import "Sales Data" and "Data extraction" (except similarCustomer.csv) files in the same root folder as of the main assignment file as they are required to present the data whereever needed.


For the SOLUTIONs :

As there is no requirement for any social media account within the given assignment, similarities and trends have still been found in the solution according the available data.
Similarly, popularity and trends have been found and their data is stored in their respective files.

The SQL code snippets used to process the solution is present in "sqlCodeSnippets.txt" file.
This snippets can be used to re-extract data saved and stored in the "Data extraction" files.
Please read that file for more details regarding the same.

Web Scraped data

This data is extracted form 'pathofstats.com' which is a gaming forum for the game 'Path of Exile League'.
This data can be used to present solutions to the questions provided.
The code snippets for the same can be found in "sqlCodeSnippets.txt" file.
For finding similar user accounts the 'Class' or 'Ladder' can clause can be put as mentioned in code snippet with the possible values mentioned in 'poeStats_tagsAssociatedClass' and 'poeStats_tagsAssociatedLadder'.