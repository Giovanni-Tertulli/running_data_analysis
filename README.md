# Apple Health and Dexcom Data Analysis

This Python project analyzes data from my Apple Health profile concerning running workouts and blood glucose levels from my Dexcom. The analysis is done to show how I am recovering after a running injury, how my training is evolving, and how running is improving my blood glucose levels. The visualizations include bar charts, line charts, and tree maps created using Plotly.

## Getting Started

### Prerequisites
Before running the Python scripts, make sure you have the following dependencies installed:

- Python 3
- Pandas
- Plotly

### Installing
1. Clone the repository to your local machine.
2. Install the required dependencies using pip:
pip install pandas plotly

### Usage
To run the analysis and generate the visualizations:

1. Open the terminal or command prompt.
2. Navigate to the directory containing the cloned repository Run the Python script:
3. Copy code
python analysis.py
The visualizations will be saved in the output/ directory.

### Data Sources

The data for this analysis is sourced from:

- Apple Health, which records running workout data, and
- Dexcom, which records blood glucose level data.

The .csv files are stored in the "./running_data" folder. Once processed, they are saved into the "./running_data_transformed" folder.

### Analysis

The analysis is focused on three main areas:

1. **Recovery after a running injury**: This analysis compares my running workout data before and after a running injury to understand how my body is recovering. The visualizations include line and bar charts of distance, duration and calorie expenditure, and tree maps heart rate zones and workout types.
2. **Training evolution**: This analysis looks at how my running workouts have evolved over the past three months. 
3. **Impact on blood glucose levels**: This analysis explores how running impacts my blood glucose levels. The visualizations include bar charts of blood glucose levels before and after a run and line charts of blood glucose trends over time.
Visualizations

The visualizations are created using Plotly, a Python library for creating interactive visualizations. The visualizations include:

- Bar charts
- Line charts
- Tree maps

License

This project is licensed under the MIT License - see the LICENSE file for details.



