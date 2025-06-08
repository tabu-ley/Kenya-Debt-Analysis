# Kenya-Debt-Analysis
## Analyzing Kenya's Debt Trends (2001-2023) using python and pandas

This is my first project. The project performs a comprehensive time series analysis of Kenya's public debt (both domestic and external) and its relationship with nominal GDP over a period of more than two decades.

The aim is to uncover trends, significant spikes, and patterns in Kenya’s debt levels and compare them against national economic growth, particularly using GDP-to-debt ratio and percentage changes over time.

## Dataset Sources
Public Debt Data: Monthly data on Kenya’s domestic and external public debt (2001–2023).

GDP Data: Annual nominal and real GDP figures for Kenya.

Both datasets are locally sourced in .csv format from the central Bank of Kenya and require preprocessing before analysis.

## Tools Used
Python

Pandas – data manipulation

NumPy – numerical operations

Seaborn & Matplotlib – data visualization

## Key Steps in the Analysis
Data Cleaning:

Removed irregular headers and rows.

Stripped white spaces from column names.

Converted debt values (entered as strings with commas) into numeric format.

Datetime Handling:

Combined year and month columns into a single datetime column.

Set datetime as index to support time series analysis.

Initial Exploration:

Plotted debt trends.

Calculated annual percentage changes in debt.

Year-over-Year Comparison:

Analyzed which years saw higher external vs domestic debt changes.

Interpreted key surges (e.g., 2009 post-crisis borrowing, 2015 SGR project impact).

Debt-to-GDP Ratio:

Joined nominal GDP data with average yearly debt figures.

Visualized the ratio over time.

Monthly Volatility:

Observed frequent changes in monthly debt, particularly post-2008.

## Visual Insights
Clear upward trend in both domestic and external debt since early 2000s.

External debt has seen more frequent spikes, especially post-2008.

Debt-to-GDP ratio has increased post-2009, indicating borrowing is outpacing economic growth.

## Insights & Context
This analysis aligns some debt surges with real-world events such as:

The 2008 global financial crisis.

Kenya’s post-election violence in 2007/2008.

SGR infrastructure project around 2014–2015.

New Constitution implementation in 2010.

## Future Work
Integrate inflation-adjusted debt for better comparison.

Include debt servicing costs.

Add fiscal deficit data for a broader economic picture.

## How to Use
Clone the repository:

git clone https://github.com/your-username/kenya-debt-analysis.git
Open and run the Jupyter notebook or Python script:

cd kenya-debt-analysis
Make sure to place the CSV files (Public Debt.csv, Annual GDP.csv) in the project folder.

## Contributing
Contributions, suggestions, or forks are welcome! Feel free to open an issue or submit a pull request.

## License
This project is open-source and available under the MIT License.
