## How to Run
Clone the repository: https://github.com/denise-cbrr/citibike-ml.git
Open `citibike.ipynb`
Run all cells top to bottom/run all

## Project structure:
```
citibike-ml/
├── citibike.ipynb   
├── citibike_data.csv
└── README.md
```

## Additional Installations
If running in Visual Studio Code (as we did), you should verify that you have the extension Google Colab VS Code Extension. If not, install it and go to this repo after cloning it and you can follow the directions under Quick Start from the link from above (attached to Google Colab). 

## Data
The cleaned dataset `citibike_data.csv` is loaded directly from GitHub inside the notebook:
df = pd.read_csv("https://raw.githubusercontent.com/denise-cbrr/citibike-ml/refs/heads/main/citibike_data.csv") 
No manual data download is required.
In the case that the csv file is not accessible, via GitHub, replace with
df = pd.read_csv(“./citibike_data.csv”)



