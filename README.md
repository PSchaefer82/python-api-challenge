# Module 6 Challenge - Python APIs
Paul Schaefer 12/21/2024

Python script in Jupiter notebook file, .ipynb

Visualizes live weather data from over 500 cities of varying distances from the equator. 
Data drawn from an API file.

Scatter plots and line regressions of the relationship between weather variables and latitude.

## Getting Started
1. Install Python on your computer
```
https://www.python.org/downloads/
```
2. Create a new environment
```
conda create -n dev python=3.10 anaconda -y
```
3. Activate the environment
```
conda activate dev
```
4. Install all the required dependencies.
```
pip install -r requirements.txt
```
5. Clone this repository to your local computer using `git clone`.
6. Download the consumer complaints dataset from the Consumer Financial Protection Bureau using the link below.
```
https://files.consumerfinance.gov/ccdb/complaints.csv.zip
```
7. Unzip the folder and add it to the cloned repository.
8. Open Visual Studio Code and download "Live Server" by navigating to "Extensions" (Ctrl + Shift + X).

**Covered in this assignment:**
create and edit panda databases
create .JSON files
read/export .csv files
generate latitude/longitude coordinates
world map marking via latitude/longitude coordinates
map marker size determined by humidity data value
filter via weather conditions and locations
search hotels from an API file, mark locations on map
calculate line regressions, r^values, p^values

**Python Dependencies:**
pandas
hvplot
matplotlib.pyplot
numpy
time
spicy.stats
json
requests
api_keys
