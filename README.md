Google Earth Engine Asset Management
====================================

Perform various Google Earth Engine (GEE) asset management tasks, for both 
legacy and cloud assets, from a local conda Python environment.

Set up
------
- If the asset management tasks will include copying assets to another user:
  - Ask to be added to the user's Cloud Assets (at least temporarily) as a 
  Principal with the Editor role, and to create a destination folder in their 
  Cloud Assets space with Writer access for your user
- Create a conda environment from `environment.yml`
- Start the notebook `manage_gee_assets.ipynb` in the environment
- Run the first cell of the notebook and follow the steps in the web-page pop up 
from Google until you can copy a code to paste into the Notebook's popup, which 
authorizes the notebook to control your GEE space 

Perform asset management tasks in the notebook
----------------------------------------------
- Review, modify, and use the examples in the notebook to perform various 
asset management tasks
