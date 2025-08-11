# Data Science Salary Dashboard

Interactive dashboard for analyzing and comparing Data Scientist salaries worldwide using Streamlit and Python visualization libraries.

https://dashboard-salary-ds.streamlit.app/

## Installation

### Prerequisites

- Python 3.13 or higher
- pip package manager

### Setup

1. Clone the repository:
```bash
git clone https://github.com/GBatriche/dashboard-salary.git
cd dashboard-salary
```

2. Create a virtual environment (recommended):
```bash
python -m venv venv

# Windows
venv\Scripts\activate

# Linux/Mac
source venv/bin/activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

1. Run the Streamlit application:
```bash
streamlit run app.py
```

2. Open your browser and navigate to `http://localhost:8501`

3. Use the sidebar controls to filter data by:
   - Country/Region
   - Experience level
   - Company size
   - Employment type

4. Explore different visualizations and interact with the charts for detailed insights

### Data Structure

Expected CSV format for salary data:
```csv
job_title,salary_usd,experience_level,employment_type,company_location,company_size,year
Data Scientist,95000,Senior,Full-time,United States,Medium,2024
```

## About

This dashboard provides comprehensive analysis of Data Scientist salaries across different countries, experience levels, and company sizes. Built with Streamlit for easy deployment and interactive data exploration.

**Key Features:**
- Global salary comparisons
- Experience level breakdown
- Company size impact analysis
- Employment type variations
- Temporal trends visualization
- Statistical summaries
- Interactive filtering

## Technologies

- **Python 3.13** - Core language
- **Streamlit** - Web application framework
- **Pandas** - Data manipulation and analysis
- **Plotly** - Interactive visualizations
- **Matplotlib** - Additional plotting capabilities

## Project Structure

```
dashboard-salary/
├── app.py                 # Main Streamlit application
├── requirements.txt       # Project dependencies
├── README.md             # Documentation
├── data/                 # Salary datasets
│   └── salary_data.csv
└── utils/               # Helper functions
    ├── data_processing.py
    └── visualizations.py
```

## Dependencies

```txt
streamlit>=1.28.0
pandas>=2.1.0
plotly>=5.17.0
matplotlib>=3.7.0
numpy>=1.24.0
```

## Deployment

### Streamlit Cloud

1. Push your code to GitHub
2. Connect your account at [Streamlit Cloud](https://streamlit.io/cloud)
3. Deploy directly from your repository

### Local Development

For development with auto-reload:
```bash
streamlit run app.py --server.runOnSave true
```

## Data Sources

The dashboard can work with various data sources:
- CSV files with salary information
- Public datasets (Kaggle, etc.)
- Company survey data
- Government statistics

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

Gabriel Batriche - [@GBatriche](https://github.com/GBatriche)

Project Link: [https://github.com/GBatriche/dashboard-salary](https://github.com/GBatriche/dashboard-salary)

## Acknowledgments

- [Streamlit](https://streamlit.io/) for the web framework
- [Plotly](https://plotly.com/) for interactive visualizations
- Data science community for insights and feedback
