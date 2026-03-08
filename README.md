# NBA PPG Forecast Demo

A Python demo to illustrate iterative forecasting with NBA player points per game data. Using a random forest model, this program focuses on closely capturing trends in NBA player's scoring performance using an online Kaggle dataset. 

## Purpose:
- Practice predictive analysis with ML
- Clean and pick model data
- Assess and improve performance with model
- Demonstrate functionality through graphs

## How to run:

1. Clone the repository
    ```bash
    git clone https://github.com/0bsinet/NBA-PPG-Prediction.git
    ```

2. Navigate into the project directory
    ```bash
    cd NBA-PPG-Prediction
    ```

3. Create a virtual environment
    ```bash
    python -m venv venv
    ```

4. Activate the virtual environment
    - **Windows:**
        ```bash
        venv\Scripts\activate
        ```
    - **Mac/Linux:**
        ```bash
        source venv/bin/activate
        ```

5. Install dependencies
    ```bash
    pip install -r requirements.txt
    ```

6. Run predictions for any player **in the dataset**
    ```bash
    python script/forecasts_util.py --player "lebron james"
    ```

7. Save the graph to a folder (optional)
    ```bash
    Save graph to file? (y/n): y
    ```


