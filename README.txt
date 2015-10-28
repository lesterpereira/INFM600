# INFM600
This is the dataset created for the INFM600 Information Organization assignment

-------
Version
-------

Version 1.0 (October 2015)

-----------
Description
-----------

    This dataset is a derivative of the Howard County Data Portal (https://data.howardcountymd.gov) 
    hosted by the Howard County governement.

    From the original dataset, only information necessary to answer the question related 
    to the the geo location of the age, restricted houses and the demoogrphic information 
    of the people, the geo location of the floodplains has been maintained. This includes
    Name, Address, City, State, Zipcode, Phone_Number, Minimum Age, Geometric_Location etc.
    
    The dataset is released in the framework of INFM 600, Information Environments, Fall
    2015, at the University of Maryland iSchool, http://ischool.umd.edu/mim.
	
-----
Files
-----
Focal Dataset

	* vAge_Restricted_Homes.csv
		This file contains the demographic information like Name, Address, City, 
                State, Zipcode, Phone_Number, Minimum Age and Geometric_Location

Supporting Dataset

	* Parks.csv
		This file contains information like FID, Name, Park_ID, Classification, Type_of_park, 
                Address1, Address2, Address3, City, Zip and Geometric_Location of all the parks loacted 
		inside Howard county 																
 	* Floodplain.csv
		This file contains FID and Geometric_Location

Merged Dataset

	* vAge_Restricted_Homes_Parks
		This data set uses the data from the focal data set and Parks.csv

-----------
Data format
-----------

   The data is formatted one entry per line as follows:
   
	* Age_Restricted_Homes.csv
		This file contains the demographic information like Name, Address, City, State, 
Zipcode, Phone_Number, Minimum Age and Geometric_Location
	
	* Parks.csv
		This file contains information like FID, Name, Park_ID, Classification, Type_of_park, 
Address1, Address2, Address3, City, Zip and Geometric_Location of all the parks loacted inside Howard county

 	* Floodplains.csv
		This file contains FID and Geometric_Location

-----------
Analysis
-----------
Are parks in Howard County accessible for elderly citizens or not?

And

Since Howard County is very prone to floods, are appropriate measures taken for the prevention of the floods, protection of the elderly folks who mostly have their residntial houses in the floodplanes?

I viewed all the three datasets taken from Howard County data portal on an interactive map and one can see that most of the age restricted homes belonging to the elderly lie in the floodplanes of Howard County and there aren't too many parks in close proximity.

------- 
License
-------
The data in the INFM600 repository is distributed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (see http://creativecommons.org/licenses/by-nc-sa/4.0/).

	The data is made available for non-commercial use. Those interested in using the data 
	in a commercial context should contact the owner(Gavish Gulati).

----------------
Acknowledgements
----------------

   I thank the Howard County Data Portal (https://data.howardcountymd.gov) 
   for hosting and allowing use of the vAge_Restricted_Homes, Parks and Floodplain 
   dataset

----------
References
----------

   When using this dataset you should cite:
   
      - the original vAge_Restricted_Homes, Parks and Floodplain dataset from Howard County Data Portal, https://data.howardcountymd.gov
      - vAge_Restricted_Homes_Parks, https://github.com/lesterpereira/INFM600
      

-------
Author
-------

   Lester Pereira
