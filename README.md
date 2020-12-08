[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/gabrielecalvo/l4w_inventory_webapp/HEAD?urlpath=voila%2Frender%2Fwebapp%2FInventoryWebApp.ipynb)

# l4w_inventory_webapp
Demo Inventory Webapp created during the 2020 Winter Semester at Language4Water Python Course

# How to create a webapp from a jupyter notebook

## 1 - Create a GitHub account (free)
[Link here](https://github.com/join)

## 2 - Create a **Public** Reporitory and upload the files
[Video tutorial](https://youtu.be/BV_9zaO4YMs), not mine but liked the music so much xD

Regarding the files to upload, you only strickly need 2 files:
- The ipynb that has the widget/dashboard/table you want to show as a webapp
- A requirement.txt file that defines the libraries that need to be installed in order for the notebook to run (which should include all third party libraries such as pandas and ipywidget **PLUS** voila and voila-material, see [mine for example](https://github.com/gabrielecalvo/l4w_inventory_webapp/blob/main/requirements.txt))

You can place the ipynb wherever you want (I have it in a webapp subfolder for example) but the requirements.txt needs to be in the main folder.

## 3 - Use MyBinder to create a WebApp from your repository
[Video tutorial](https://youtu.be/VtchVpoSdoQ?t=1126) the part you want starts at 18:46 and ends at 19:44

In my case I just:
  - went to [https://mybinder.org/](https://mybinder.org/)
  - put `gabrielecalvo/l4w_inventory_webapp` as GitHub repository 
  - put `voila/render/webapp/InventoryWebApp.ipynb` as path (`voila/render` are needed to tell mybinder to use voila' to rended the notebook, the rest is the path to the notebook from the main folder of your repository, in my case `webapp/InventoryWebApp.ipynb`)
  - changed the dropdown from *File* to *Url* 
  - and finally clicked *launch*. 
  
The link I can share with people is just below! :)
