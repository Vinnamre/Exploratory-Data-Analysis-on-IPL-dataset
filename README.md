

# IPL Dataset Exploratory Data Analysis (EDA)

This repository contains an Exploratory Data Analysis (EDA) of the **Indian Premier League (IPL)** dataset. The EDA helps in understanding the distribution, trends, and hidden patterns within the IPL matches and player performances.

![IPL Logo](https://upload.wikimedia.org/wikipedia/en/thumb/a/a1/IPL_2022_logo.svg/1200px-IPL_2022_logo.svg.png)

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset Information](#dataset-information)
3. [Installation and Setup](#installation-and-setup)
4. [Exploratory Data Analysis](#exploratory-data-analysis)
    - [Data Cleaning](#data-cleaning)
    - [Data Visualization](#data-visualization)
5. [Key Insights](#key-insights)
6. [Results](#results)
7. [Contributing](#contributing)
8. [License](#license)

---

## Project Overview
The goal of this project is to perform an in-depth **Exploratory Data Analysis (EDA)** on the IPL dataset. We aim to uncover insights regarding team performance, individual player statistics, venue advantages, and factors influencing match outcomes.

## Dataset Information
The dataset contains information on IPL matches, teams, and individual performances. The main features of the dataset include:
- **Match data**: Date, venue, teams, results
- **Player data**: Runs scored, wickets taken, and strike rates
- **Venue data**: City, stadium
- **Other**: Toss details, match result (win by runs/wickets)

## Installation and Setup
To run the analysis locally, follow the steps below:

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/IPL-EDA.git
   cd IPL-EDA
   ```

2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter notebook:
   ```bash
   jupyter notebook IPL_EDA.ipynb
   ```

## Exploratory Data Analysis

### Data Cleaning
Initial steps in the analysis include:
- Handling missing values
- Removing or fixing duplicates
- Converting data types

### Data Visualization
We use various libraries such as **Matplotlib** and **Seaborn** for visualizing the dataset.

Here are some of the key visualizations:
1. **Win Distribution by Teams**
   ![Wins by Teams](images/wins_by_team.png)

2. **Top Run Scorers**
   ![Top Run Scorers](images/top_run_scorers.png)

3. **Matches Won by Toss Decision**
   ![Toss Decision Impact](images/toss_decision_impact.png)

## Key Insights
- Teams winning the toss tend to choose batting or bowling based on the venue's conditions.
- The highest number of runs are typically scored at specific venues.
- Certain players consistently perform well across different IPL seasons.

## Results
The EDA revealed various important aspects of IPL matches, such as:
- **Winning strategies**: Factors influencing a team’s win, like toss decision and home ground advantage.
- **Player performance**: Identifying top performers by runs, wickets, and other critical metrics.
- **Venue analysis**: Key grounds where teams tend to perform better.

## Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request for any feature suggestions, issues, or data improvements.

---

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to fork the repository and provide your insights or improvements.

---

### Contact
For any queries, contact [your-email@example.com](mailto:your-email@example.com).

---

This `README.md` file outlines the project structure, with code blocks, tables, and images for visual appeal. Ensure the referenced images are saved in the `images/` folder of your project.


