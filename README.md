# Hotel Booking Analysis Project

## Overview
This project analyzes hotel bookings utilizing a dataset from two specific hotels: one located in a city and the other in a resort area. It encompasses reservation status, booking details, guest demographics, country of origin, market segment, distribution channel, room types, and more.

## Goals
The main goals of this project are:
- Gain insights into guest behaviors, booking patterns, and cancellations.
- Inform strategic decisions in the hospitality industry.

## Business Questions
1. **Geographical Insights**: Where do our guests predominantly come from?
2. **Seasonal Patterns**: During which times of the year do we observe increased booking activity?
3. **Booking Channel Performance**: Which booking channels contribute the most reservations?
4. **Cancellations Analysis**: What factors contribute to booking cancellations? How does market segmentation influence cancellations?

## Data Source
The dataset used in this project was obtained from [Kaggle](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand). It includes information on hotel bookings, guest demographics, booking details, and more. The dataset was collected from two hotels: one located in a city and the other in a resort area. It was collected for the purpose of analyzing hotel booking demand and related factors, aligning with the main goals of this project.

## File Structure
- `notebooks/hotel_data.ipynb`: Jupyter notebook containing the main script for analyzing hotel bookings.
- `data/`: Directory containing the dataset.
- `images/`: Directory containing charts in .png format.
- `slides/`: Directory containing information about the presentation.
- `README.md`: This file providing an overview of the project.


## Methodology
For this analysis, a straightforward approach was taken. The dataset was cleaned to ensure accuracy and completeness, handling missing values and duplicates. The analysis primarily involved calculating averages and transforming values into percentages to perform exploratory data analysis (EDA) statistics. Python and various libraries were utilized for data manipulation, visualization, and statistical analysis.

## Results
### Geographical Insights
Most guests come from PRT, followed by GRB and FRA.

### Seasonal Patterns
The busiest periods for both hotels are observed from March until June and August until October.

### Booking Channel Performance
TA/TO channels are responsible for the majority of reservations.

### Cancellations Analysis
- As lead time increases, the probability of cancellation decreases.
- 61% of group bookings end in cancellations, indicating a significant cancellation rate within this segment.

## Technologies Used
This project is implemented in Python and utilizes various libraries for data analysis and visualization. Refer to the `requirements-dev.txt` file for the required libraries.

## Installation
To set up the project environment, install the required dependencies listed in the `requirements.txt` file.

```bash
pip install -r requirements.txt
