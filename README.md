# Real Estate Statistics Analysis & Data Visualization
Statistical analysis on real estate, related business, and affordable housing topics. United States National scope with a periodic focus in Philadelphia, PA

View repository as a GitHub Page at https://data-design-dimension.github.io/real-estate-stats/


## Does the presence of local banks affect home mortgages?
Deferred project (need input and data cleansing and preparation for bank locations dataset)...

There is a long history of financial institutions as actors in the de jure segregation of United States history. Read this article for a short primer on that background: https://www.smithsonianmag.com/history/how-federal-government-intentionally-racially-segregated-american-cities-180963494/

Having personally lived in a neighborhood which has welcomed its first bank after lacking one for over 30 years, during which time I gradually moved my accounts to online only banks, I've wondered what affect does a local brick and mortal establishment have today on home mortgage lending, if any, and is it any more equitable?

Data sources include predominantly:
-Urban Institute datasets available through https://www.opendataphilly.org/
-FDIC: Federal Deposit Insurance Corporation bank locations available through https://www.fdic.gov
-Census Core-Based Statistical Area (CBSA) to Federal Information Processing Series (FIPS) County Crosswalk, National Bureau of Economic Research available through https://www.nber.org/research/data/census-core-based-statistical-area-cbsa-federal-information-processing-series-fips-county-crosswalk

Direct URL addresses for specific datasets used are in the R Markdown file(s).

For this analysis, I found that it was challenging to link data from the FDIC of local banks and branch locations with the data of the mortgage disclosures, due to varying location references. I was unable to do this down to a meaningful neighbor or census tract level to the extent where I would expect to see a degree of change within urban areas.


## Finding Contiguous Properties project
Under construction...

For the use case of identifying adjacent properties suitable for owner-occupied income producing home ownership under Veterans Administration mortgage funding, the neighbors.py file is being used as permitted under copyright by Ujaval Gandhi.




## Fair Market Value and LLC Ownership Analysis project

<img src="/output/ggplot_FMV_sidebyside_Sales_Price_-_Non-LLC_Buyers-1.png" alt="graph of real estate sales prices by buyers that are an LLC entity beside a graph of the same for those buyers who are not an LLC entity">

Data sources include OpenDataPhilly datasets available through https://datacatalog.urban.org/search/type/dataset
Direct URL addresses for specific datasets used are in the Python Jupyter Notebook or R Markdown file(s).

You may wish to open this project directly in RStudio with file /Kathryn_Hurchla_FMV_and_LLC_project.Rproj

Some script is commented out relating to PostgreSQL API connections. 
You may either modify those chunks to directly query the API from the script, or query the API separately to save a file to run the script on.




General Disclaimer: This research is completed by individuals and is not a reflection in any way of the City of Philadelphia departments or its affiliates.

<!-- my custom buy me and a mentee a tea button -->
<a href="https://www.buymeacoffee.com/earthtokathy"><img src="https://img.buymeacoffee.com/button-api/?text=Fuel mentorship with tea&emoji=🍵&slug=earthtokathy&button_colour=ecd0df&font_colour=062D3F&font_family=Poppins&outline_colour=000000&coffee_colour=FFDD00"></a>

<!-- standard buy me a coffee orange button for reference -->
<!-- <a href="https://www.buymeacoffee.com/earthtokathy" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a> -->
