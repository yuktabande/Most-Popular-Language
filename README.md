# Analysis of Programming Language Popularity Using Stack Overflow Tags

## Project Overview
This project analyzes the popularity of programming languages by examining tags from posts on Stack Overflow. Stack Overflow is a widely-used Q&A platform where tags categorize questions by topic, technology, or language. By aggregating and analyzing these tags, the project aims to uncover trends and shifts in the developer community over time.

## Features
- **Data Collection:** Extract tags from Stack Overflow posts related to programming languages.
- **Data Cleaning:** Process the data to remove irrelevant tags and duplicates.
- **Data Analysis:** Identify the most popular programming languages by tag frequency and analyze trends over time.
- **Data Visualization:** Generate visualizations to represent the popularity and trends of different programming languages.

## Usage
- **Data Collection:**
- - **If using an API:** Ensure you have your Stack Overflow API credentials.
  - **If using a pre-existing dataset:** Place the dataset in the data/ directory.
- **Run Data Analysis:**
- - ```
    python analyze_data.py
- **Generate Visualizations:**
- - Visualization scripts are located in the visualizations/ directory. Run them to generate charts and graphs.
    
## Project Structure
```
  project-root/
│
├── data/                   # Raw and processed data
├── notebooks/              # Jupyter notebooks for data exploration and analysis
├── scripts/                # Python scripts for data collection and processing
├── visualizations/         # Scripts to generate visualizations
├── requirements.txt        # List of dependencies
└── README.md               # Project documentation

```

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your proposed changes.

## Contact
For any questions or issues, please open an issue on GitHub or contact-yuktaabande@gmail.com.
