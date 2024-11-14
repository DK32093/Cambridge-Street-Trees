# Cambridge-Street-Trees

This project was a fun way to practice some of my geospatial Python skills. I chose to use data from my home city of Cambridge, Massachusetts available through the fantastic [Cambridge GIS website](https://www.cambridgema.gov/GIS).

I used the city’s base zoning districts and grouped them into the [broad categories provided here](https://www.cambridgema.gov/-/media/Files/CDD/Maps/Zoning/cddmap_zoning_base_11x17_20240221.pdf). I also obtained point data representing street trees. I then used the OSMnx and GeoPandas Python libraries to calculate the total road length in each district using OpenStreetMap data. Finally, I calculated the number of street trees per meter of road for each zone category and extracted the most common tree species.

This was a fun way to practice working with vector layers and creating geospatial graphics using only Python. I took inspiration for this project from the great [Python Foundation series](https://www.youtube.com/playlist?list=PLppGmFLhQ1HJspXSA0asH9kw1OhlLrxHT) by Spatial Thoughts and [Luigi Carboni’s project](https://nbviewer.org/github/luicarboni/My_Projects/blob/master/Starting_with_OSMnx.ipynb) Retrieving and Visualizing Data from OpenStreetMap.

[View the code here](Cambridge_Zones_Trees.ipynb)

[View the Street trees data here](https://www.cambridgema.gov/GIS/gisdatadictionary/Environmental/ENVIRONMENTAL_StreetTrees![image](https://github.com/user-attachments/assets/2577e753-f69f-467d-a414-18b704d9c86e))

[View the zones data here](https://www.cambridgema.gov/GIS/gisdatadictionary/CDD/CDD_ZoningDistricts![image](https://github.com/user-attachments/assets/8c78f77a-b328-4a95-a2b1-276f2cccc0ed))

![image](https://github.com/user-attachments/assets/e8fc942b-1d7f-4563-9bf5-bfe109570609)
