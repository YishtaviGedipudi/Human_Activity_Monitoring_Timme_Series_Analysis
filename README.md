

# Human Activity Monitoring: Time Series Analysis

Unlock the secrets of human movement! This project dives deep into analyzing accelerometer data using advanced graph-based methods to monitor various human activities like walking, running, and climbing. Let's turn raw motion data into meaningful insights!

## 📊 Project Overview

Human activity monitoring is essential in various fields, from healthcare to sports science. This project leverages time series analysis to explore accelerometer data for 15 subjects performing different activities, including walking, running, climbing up, and climbing down stairs.

### Key Features

- **Natural Visibility Graph (NVG) and Horizontal Visibility Graph (HVG)**: Transform time series data into graphs to reveal hidden patterns.
- **Graph-Based Metrics**: Compute average degree, network diameter, and average path length for meaningful insights.
- **Permutation Entropy and Complexity**: Quantify the randomness and structure in the time series data to distinguish different activities.
- **Data Visualization**: Create scatter plots to visualize relationships between computed metrics and activities.

## 🚀 Getting Started

### Prerequisites

- Python 3.7 or higher
- Jupyter Notebook
- Required packages:
  - `ts2vg`
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `pycairo` (for specific graph operations)

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/Human-Activity-Monitoring-Time-Series-Analysis.git
   cd Human-Activity-Monitoring-Time-Series-Analysis
   ```

2. Install the necessary packages:

   ```bash
   pip install -r requirements.txt
   ```

### Usage

1. Open the Jupyter Notebook:

   ```bash
   jupyter notebook human_activity_analysis_time_series.ipynb
   ```

2. Follow the code and run the cells step-by-step to perform the analysis.

## 📈 Data Analysis Tasks

### Task 1: Graph-Based Methods

1. Apply NVG and HVG to accelerometer data.
2. Compute metrics: average degree, network diameter, and average path length.
3. Visualize results with scatter plots colored by activity type.

### Task 2: Entropy and Complexity

1. Compute permutation entropy and complexity.
2. Analyze various parameters: embedded dimension, embedded delay, and signal length.
3. Visualize relationships between entropy and complexity for different activities.

## 📁 Dataset

The dataset contains accelerometer data for 15 subjects, capturing activities like walking, running, climbing up, and climbing down. You can access the data [here](#) (add your data link).

## 🎨 Visualizations

- Scatter plots for graph-based metrics.
- Scatter plots for entropy vs. complexity.
