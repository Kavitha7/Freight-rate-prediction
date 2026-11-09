## Freight rate prediction

## Objective:

To predict freight rate for every load using Machine learning model to support daily operations of the company.

## Data:

Three sets of data are given as:
1. Train-Test data (Contains columns: load_id, pickup, delivery, pickup_lat, pickup_lon, delivery_lat, delivery_lon, distance, equipment, weight, date, market_index, quote_signal and posted_rate).
2. Validation data (Contains all the columns mentioned in train-test data except the posting_rate).
3. December chart inputs (contains columns: pickup, delivery, distance, equipment and date. Except for the date column, values for the remaining columns are fixed).

## Data Analysis:

Analysis consists of following steps.
1. Data processing.
2. Understanding the given data.
3. Feature engineering.
4. Exploratory data analysis.
5. Model building.
6. Generating predictions for validation set.
7. Generating fixed December prediction chart using the scorer.
