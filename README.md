
## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required Python libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/NamousNassim/SegmentationKmeans.git
    cd SegmentationKmeans
    ```

2. Install the required libraries:
    ```sh
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```

### Running the Notebook

1. Open Jupyter Notebook:
    ```sh
    jupyter notebook
    ```

2. Open the `Segmentation_using_K_Means.ipynb` notebook and run the cells to perform customer segmentation.

## Data

The dataset `Mall_Customers.csv` contains the following columns:
- `CustomerID`: Unique ID for each customer
- `Gender`: Gender of the customer
- `Age`: Age of the customer
- `Annual Income (k$)`: Annual income of the customer in thousands of dollars
- `Spending Score (1-100)`: Score assigned by the mall based on customer behavior and spending nature

## Analysis

The notebook performs the following steps:
1. Load and display the dataset.
2. Perform exploratory data analysis (EDA).
3. Apply the K-Means clustering algorithm to segment customers.
4. Visualize the clusters.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The dataset is provided by the mall for customer analysis.
- The K-Means algorithm is implemented using the `scikit-learn` library.
