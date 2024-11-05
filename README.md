
# Video Game Sales Analysis

This project analyzes video game sales data across different platforms, genres, and regions. The dataset provides insights into the top-selling games, trends across regions, and sales patterns based on year, genre, and publisher.

## Dataset Overview

The data file, `vgsales.csv`, contains 16,598 records and 11 columns:

- **Rank**: Sales ranking by global sales.
- **Name**: Video game title.
- **Platform**: Platform on which the game was released (e.g., Wii, NES).
- **Year**: Release year.
- **Genre**: Game genre (e.g., Action, Sports).
- **Publisher**: Game publisher.
- **NA_Sales**: Sales in North America (in millions).
- **EU_Sales**: Sales in Europe (in millions).
- **JP_Sales**: Sales in Japan (in millions).
- **Other_Sales**: Sales in other regions (in millions).
- **Global_Sales**: Total global sales (in millions).

## Project Structure

- **Data Analysis and Visualization**: Exploration of trends in global and regional video game sales, including:
  - Top-selling games and their publishers.
  - Sales distribution across genres and platforms.
  - Regional sales patterns.
  - Yearly trends in game sales.
  
- **Machine Learning (Optional)**: Possible exploration of predictive models to estimate sales based on game attributes.

## Dependencies

To run this analysis, you will need the following Python libraries:
- `pandas` for data manipulation.
- `matplotlib` and `seaborn` for visualization.

Install dependencies using:
```bash
pip install pandas matplotlib seaborn
```

## Getting Started

1. **Load the Dataset**:
   Use `pandas` to load and explore `vgsales.csv`.
   ```python
   import pandas as pd
   vgsales_df = pd.read_csv('vgsales.csv')
   ```

2. **Explore Data**:
   - Check for missing values.
   - Analyze sales distributions across regions.

3. **Analyze Trends**:
   - Identify top-selling games and publishers.
   - Examine the popularity of genres and platforms over time.
   - Visualize sales data using `matplotlib` and `seaborn`.

4. **Optional - Model Building**:
   - Build a machine learning model to predict `Global_Sales` based on features like `Platform`, `Genre`, `Year`, etc.

## Example Analysis

Here are some analysis questions you could explore with this dataset:
- What are the top 10 best-selling video games globally?
- How do game genres vary in popularity across different regions?
- Which platforms have generated the most sales in North America?
- How have global video game sales trended over the years?

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
