# MFI - Financial Analysis Project

A comprehensive financial analysis project analyzing multiple sectors of the Nepalese market including banking, finance, investment, insurance, and more using Jupyter Notebooks and Python.

## Project Overview

This project contains detailed financial analysis notebooks for various sectors:

- **Banking** - Analysis of banking sector data
- **DevBank** - Development bank sector analysis
- **Finance** - General finance sector analysis
- **Hotel & Tourism** - Hotel and tourism industry analysis
- **Hydropower** - Hydropower sector analysis
- **Investment** - Investment market analysis
- **Life Insurance** - Life insurance sector analysis
- **Manufacturing & Production** - Manufacturing industry analysis
- **Microfinance** - Microfinance sector analysis
- **NEPSE** - Nepal Stock Exchange analysis
- **Non-Life Insurance** - General insurance analysis
- **Others** - Miscellaneous financial sectors
- **Trading** - Trading sector analysis
- **Combined** - Consolidated analysis across sectors

## Project Structure

```
MFI/
├── Banking/
│   ├── banking.csv
│   └── Banking.ipynb
├── DevBank/
│   ├── DevBank.csv
│   └── DevBank.ipynb
├── Finance/
│   ├── Finance.csv
│   └── Finance.ipynb
├── HotelToursim/
│   ├── Hotel.csv
│   └── Hotel.ipynb
├── Hydropower/
│   ├── Hydropower.csv
│   └── Hydropower.ipynb
├── Investment/
│   ├── Investment.csv
│   └── Investment.ipynb
├── Life Insurance/
│   ├── Life Insurance.csv
│   └── Life Insurance.ipynb
├── Manu.& Pro/
│   ├── Manu.&Pro..csv
│   └── Manu.&Pro..ipynb
├── Microfinance/
│   ├── Microfinance.csv
│   └── Microfinance.ipynb
├── NEPSE/
│   ├── nepse.csv
│   └── nepse.ipynb
├── NonLifeInsurance/
│   ├── Nonlife.csv
│   └── Nonlife.ipynb
├── others/
│   ├── Others.csv
│   └── Others.ipynb
├── Trading/
│   ├── Trading.csv
│   └── Trading.ipynb
└── Combined/
    ├── Final.ipynb
    └── data/
```

## Setup Instructions

### Prerequisites

- Python 3.8 or higher
- pip or conda package manager
- Git

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/YOUR_USERNAME/MFI.git
   cd MFI
   ```

2. **Create a virtual environment** (recommended)

   ```bash
   # Using venv
   python -m venv venv

   # Activate virtual environment
   # On Windows:
   venv\Scripts\activate
   # On macOS/Linux:
   source venv/bin/activate
   ```

3. **Install required packages**

   ```bash
   pip install -r requirements.txt
   ```

   If you don't have a requirements.txt file, install common packages:

   ```bash
   pip install jupyter pandas numpy matplotlib seaborn scikit-learn openpyxl
   ```

4. **Start Jupyter Notebook**

   ```bash
   jupyter notebook
   ```

5. **Open a notebook** - Navigate to any sector folder and open the `.ipynb` file (e.g., `Banking/Banking.ipynb`)

## Usage

Each sector folder contains:

- **CSV file** - Raw data for that sector
- **Jupyter Notebook** - Analysis, visualizations, and insights

To run the analysis:

1. Open a notebook in Jupyter
2. Run cells sequentially using `Shift + Enter`
3. View the generated visualizations and analysis results

## Contributing

To contribute to this project:

1. Create a new branch for your changes
2. Make your modifications
3. Commit with clear messages
4. Push to GitHub and create a pull request

## License

This project is open source. Please specify your license here (MIT, Apache 2.0, etc.)

## Contact

For questions or issues, please open an issue on GitHub or contact the project maintainer.

## Future Enhancements

- Add data validation and cleaning procedures
- Implement automated reporting
- Create interactive dashboards
- Add unit tests for analysis functions
- Expand data sources

---

**Last Updated:** March 2026
