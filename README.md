Birth Rates for Belgian Municipalities - A Short Analysis of the Differences
-----------------------

This project will get a glimpse of the Belgium natality data and try to find the reasons for differences between municipalities<br>
If you only wish to view the final result, you can open the [Jupyter notebook](https://github.com/alexbraila/belgian-birth-rates/blob/master/Birth%20Rates%20for%20Belgian%20Municipalities%20-%20A%20Short%20Analysis%20of%20the%20Differences.ipynb), otherwise, you can install everything locally by following the below instructions

Installation
----------------------

### Download the data

* Clone this repo to your computer
* Get into the folder using `cd belgian-birth-rates`
* Run `mkdir data`
* Switch into the `data` directory using `cd data`
* Download the data files into the `data` directory
    * from STATBEL
    	* You can find the data
        	* [here](https://statbel.fgov.be/fr/themes/population/structure-de-la-population#figures), files Population de droit par commune au 1 janvier (2011-2018) and Nombre de ménages par commune selon le type
			* [here](https://statbel.fgov.be/fr/themes/population/naissances-et-fecondite#figures), files Naissances et fécondité 2011 through Naissances et fécondité 2015
            * [here](https://statbel.fgov.be/fr/open-data?category=23), files Population par lieu de résidence, nationalité, état civil, âge et sexe 2011 through 2015
    * from [HyperCarte](http://hypercarte.imag.fr/hypotheque.html#Belgique), file structure_be.xls
    * from [GitHub](https://github.com/Datafable/rolling-blackout-belgium/tree/master/data/geospatial), file municipalities-belgium.geojson
* Switch back into the `belgian-birth-rates` directory using `cd ..`

### Install the requirements
 
* Install Anaconda
* Install the requirements using `pip install -r requirements.txt`
    * Make sure you use Python 3

Usage
-----------------------

* Launch the Jupyter Notebook App and start the notebook `Birth Rates for Belgian Municipalities - A Short Analysis of the Differences.ipynb`
* Run the whole notebook
