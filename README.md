# Police Shootings in the United States: 2015-2024

This project analyzes data on fatal police shootings in the United States, compiled by *The Washington Post*. The dataset spans from 2015 to 2024 and provides detailed information on each incident, including:

- Victim's name, age, gender, and race  
- Whether the victim was armed  
- Circumstances of the encounter  
- Police departments involved  

The goal is to enhance accountability and transparency in law enforcement through comprehensive data analysis.

## Dataset Overview

The dataset includes key columns such as:

- **ID**: Unique identifier for each incident  
- **Date**: Date of the shooting  
- **Name**: Name of the victim  
- **Age**: Age of the victim  
- **Gender**: Gender of the victim (Male/Female)  
- **Race**: Race of the victim  
- **Armed**: Whether the victim was armed  
- **City/State**: Location of the incident  
- **Mental_illness**: Indicator if the victim had mental health issues  
- **Fleeing**: Whether the victim was fleeing at the time of the encounter  

## Project Structure

- **Data Loading**: The dataset is loaded from Google Drive or via manual upload.  
- **Libraries Used**:  
  - `pandas` for data manipulation  
  - `numpy` for numerical computations  
- **Exploratory Data Analysis (EDA)**: Insights into patterns in the data, including breakdowns by race, gender, and year.  

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/brunoribeirol/police-shootings-usa.git
   cd police-shootings-usa
   ```
   
2. Run the notebook locally:
- Ensure you have Jupyter Notebook or Jupyter Lab installed.
- Install required dependencies:
  ```bash
  pip install pandas numpy
  ```
- Launch the notebook:
  ```bash
  jupyter notebook police_shootings_usa.ipynb
  ```
    
## Analysis Highlights
- **Trends Over Time**: Examine how the frequency of police shootings has changed year by year.
- **Demographic Disparities**: Explore differences in police shootings based on race, gender, and age.
- **Mental Health Considerations**: Analyze the proportion of victims with reported mental health issues.
- **Fleeing Incidents**: Study the role of fleeing behavior in fatal encounters.

## Contributing
- Contributions are welcome! Please follow these steps to contribute:
1. Fork the repository.
2. Create a new branch (git checkout -b feature/YourFeatureName).
3. Commit your changes (git commit -m 'Add some feature').
4. Push to the branch (git push origin feature/YourFeatureName).
5. Open a pull request.
   
## License
This project is licensed under the MIT License.


