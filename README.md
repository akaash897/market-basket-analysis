# Market Basket Analysis using Association Rule Mining

## Team Members

- Akaash Chatterjee - M24CSE002
- Aman Saini - M24CSE003
- Bera Swaminath Ansuman Sabita - M24CSE007

## Package Requirements

To run the code in this project, you need the following packages and libraries:

- pandas
- numpy
- matplotlib
- seaborn
- itertools (standard library)
- networkx
- tabulate
- openpyxl

You can install the required packages using the following command:

```sh
pip install pandas numpy matplotlib seaborn networkx tabulate openpyxl
```

## Dataset

The dataset used in this project is the "Online Retail" dataset from the UCI Machine Learning Repository. This dataset contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

You can download the dataset from the following link:

- [Online Retail Dataset](https://archive.ics.uci.edu/dataset/352/online+retail)

## Run Instructions

Follow these steps to set up the environment and execute the code:

1. **Clone the repository:**
    ```sh
    git clone https://github.com/yourusername/market-basket-analysis.git
    cd market-basket-analysis
    ```

2. **Install the required packages:**
    ```sh
    pip install -r requirements.txt
    ```
    Alternatively, you can manually install the packages using the command mentioned in the "Package Requirements" section.

3. **Download the dataset:**
    Download the dataset from UCI Machine Learning Repository and place it in the project directory.

4. **Run the Jupyter Notebook:**
    Open the Jupyter Notebook and run the cells to execute the code.
    ```sh
    jupyter notebook Market_Basket_Analysis_using_Association_Rule_Mining.ipynb
    ```

5. **Follow the instructions in the notebook:**
    The notebook contains step-by-step instructions and code to perform market basket analysis using association rule mining. Follow the instructions and run the cells sequentially to see the results.

## Running on Google Colab

If you prefer to run the project on Google Colab, follow these steps:

1. **Open Google Colab:**
    Go to [Google Colab](https://colab.research.google.com/).

2. **Clone the repository:**
    In a new notebook, run the following code to clone the repository:
    ```python
    !git clone https://github.com/yourusername/market-basket-analysis.git
    %cd market-basket-analysis
    ```

3. **Install the required packages:**
    Run the following code to install the required packages:
    ```python
    !pip install pandas numpy matplotlib seaborn networkx tabulate openpyxl
    ```

4. **Upload the dataset:**
    Upload the dataset to the Colab environment. You can use the file upload feature in Colab to upload the dataset.

5. **Run the Jupyter Notebook:**
    Open the Jupyter Notebook and run the cells to execute the code:
    ```python
    from google.colab import drive
    drive.mount('/content/drive')
    !jupyter nbconvert --to notebook --execute Market_Basket_Analysis_using_Association_Rule_Mining.ipynb
    ```

6. **Follow the instructions in the notebook:**
    The notebook contains step-by-step instructions and code to perform market basket analysis using association rule mining. Follow the instructions and run the cells sequentially to see the results.

## Results

The results of the market basket analysis will be displayed in the Jupyter Notebook/ Google Colab. You will see various visualizations and tables that summarize the association rules and their metrics such as support, confidence, and lift.

## References

- [Pandas Documentation](https://pandas.pydata.org/pandas-docs/stable/)
- [NumPy Documentation](https://numpy.org/doc/)
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)
- [Seaborn Documentation](https://seaborn.pydata.org/)
- [NetworkX Documentation](https://networkx.github.io/documentation/stable/)
- [Tabulate Documentation](https://pypi.org/project/tabulate/)
- [Openpyxl Documentation](https://openpyxl.readthedocs.io/en/stable/)
- [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php)

## Dataset

The dataset used in this project is the "Online Retail" dataset from the UCI Machine Learning Repository. You can download it from the following link:

- [Online Retail Dataset](https://archive.ics.uci.edu/dataset/352/online+retail)