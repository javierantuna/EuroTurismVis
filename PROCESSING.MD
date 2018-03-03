At the beginning, we obtained data from the World Bank web-site in Excel format.

After that, we had to erase the columns of data which we will not use for the project.

The next step was to remove countries which do not belong to the European Union and those that do not provided enough data.

Then, we built a CSV file from the Excel file and we substituted semicolons ';' by commas ',' so that the algorithm implemented in D3 is able to read the data properly.

We also had to work on the file that contains the interactions among the countries. The first action we did with this file was to check its data. It was found out that the data contained in this file did not show the data which we got before as for the number of departures and arrivals for each country. For this reason, we had to modify the data to obtain logical results that could be represented. This whole process was done by hand.

Once data was all checked and completed, we made some calculations on Excel sheets. For example, the percentage representing the arrivals and departures from/to each country to/from the others has been calculated this way. Finally, we had to transform these files in CSV format in order to be read, by modifying the "," by ".", and the ";" by ",".