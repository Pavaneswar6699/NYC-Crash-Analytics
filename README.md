# NYC Crash Analytics Dashboard

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-Latest-red?logo=streamlit)
![License](https://img.shields.io/badge/License-MIT-green)

A comprehensive **Streamlit-based interactive dashboard** for analyzing motor vehicle collisions across New York City. This project provides real-time visualizations and actionable insights into traffic patterns, collision trends, and safety metrics.

## 📊 Features

- **Interactive Maps**: Visualize collision hotspots across NYC using geographic mapping
- **Temporal Analysis**: Track collision trends over time with time-series charts
- **Data Filtering**: Filter collisions by date range, borough, and severity
- **Statistical Insights**: View aggregated statistics and key metrics
- **Performance Metrics**: Analyze contributing factors and injury statistics
- **Responsive Design**: Mobile-friendly and desktop-optimized interface

## 🎯 Use Cases

- **Traffic Safety Analysis**: Identify dangerous intersections and areas
- **Urban Planning**: Support data-driven infrastructure improvements
- **Insurance & Risk Analysis**: Assess collision rates and patterns
- **Public Safety**: Support emergency response planning

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- pip (Python package manager)

### Installation

```bash
# Clone the repository
git clone https://github.com/Pavaneswar6699/NYC-Crash-Analytics.git
cd NYC-Crash-Analytics

# Install dependencies
pip install -r requirements.txt
```

### Running the Dashboard

```bash
streamlit run app.py
```

The dashboard will open in your default browser at `http://localhost:8501`

## 📁 Project Structure

```
NYC-Crash-Analytics/
├── app.py                 # Main Streamlit application
├── requirements.txt       # Python dependencies
├── data/                  # Data files
├── utils/                 # Utility functions
└── README.md              # Project documentation
```

## 📚 Data Source

This project uses NYC motor vehicle collision data, which includes:
- Collision timestamps
- Geographic coordinates (latitude, longitude)
- Number of injuries and fatalities
- Contributing factors
- Borough and street information

## 🛠️ Technologies Used

- **Streamlit**: Interactive web framework for data applications
- **Pandas**: Data manipulation and analysis
- **Plotly**: Interactive visualizations
- **NumPy**: Numerical computing
- **Folium**: Interactive mapping

## 💡 Key Insights

The dashboard enables users to:
- Discover peak collision hours and seasons
- Identify high-risk areas requiring attention
- Analyze collision severity by location
- Track trends over multiple years

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

### Steps to Contribute

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -m 'Add improvement'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👤 Author

**Pavaneswar6699**

- GitHub: [@Pavaneswar6699](https://github.com/Pavaneswar6699)

## 🙏 Acknowledgments

- New York City Open Data for providing collision data
- Streamlit community for excellent documentation
- Data visualization libraries: Plotly and Folium

---

**Last Updated**: April 27, 2026
