# EDA On Hotel Booking Analysis
Exploratory Data Analysis of hotel booking dataset using Python.

## Business Context

This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things.
This hotel booking dataset can help to explore and analyse general trends in hotel bookings.

## Business Objective

The Hotel Booking Analysis project aimed to conduct an exploratory data analysis(EDA) on hotel booking data to identify patterns and insights that could help hotel managers make informed decisions like :-

- How to increase bookings and revenue?
- Reason for cancellation
- Who cancels more?
- Which agent generate more revenue?
- Which food and room type generates more revenue?


## Dataset Description and Data Dictionary

- The given dataset has booking information of City and Resort Hotels.
- It has total 119390 rows and 32 columns.
- Data Dictionary :-
<table>
  <tr>
    <th>Field </th>
    <th>Description</th>
  </tr>
  <tr>
    <td>Hotel</td>
    <td>Type of hotel (City Hotel and Resort Hotel)</td>
  </tr>
  <tr>
    <td>is_cancelled</td>
    <td>(1) If the booking was cancelled or (0) for not cancelled</td>
  </tr>
  <tr>
    <td>lead_time</td>
    <td>time (in days) between the date of booking and the actual arrival</td>
  <tr>
      <td>arrival_date_year</td>
      <td>Year of arrival date</td>
    </tr>
    <tr>
      <td>arrival_date_month</td>
      <td>Month of arrival date</td>
    </tr>
    <tr>
      <td>arrival_date_week_number</td>
      <td>Week number of arrival date</td>
    </tr>
    <tr>
      <td>arrival_date_day_of_month</td>
      <td>Day of arrival date</td>
    </tr>
    <tr>
      <td>stays_in_weekend_nights</td>
      <td>Number of weekend nights(Saturday or Sunday) spent by guest in  hotel</td>
    </tr>
    <tr>
      <td>stays_in_week_nights</td>
      <td>Number of week nights(Monday to Friday) spent by guest in hotel</td>
    </tr>
    <tr>
      <td>adults</td>
      <td>Number of adults</td>
    </tr>
    <tr>
      <td>children</td>
      <td>Number of children</td>
    </tr>
    <tr>
      <td>babies</td>
      <td>Number of babies</td>
    </tr>
    <tr>
      <td>meal</td>
      <td>Type of meal opted by guest</td>
    </tr>
    <tr>
      <td>country</td>
      <td>Country code of guest</td>
    </tr>
    <tr>
      <td>market_segment</td>
      <td>Which segment the customer belongs to</td>
    </tr>
    <tr>
      <td>distribution_channel</td>
      <td>from which channel customer accessed the stay - corporate booking/Direct/T.A.TO</td>
    </tr>
    <tr>
      <td>is_repeated_guest</td>
      <td>If the guest coming for first time or not (0 for first time and 1 for repeated)</td>
    </tr>
    <tr>
      <td>previous_cancellations</td>
      <td>Total number of previous cancelled bookings</td>
    </tr>
    <tr>
      <td>previous_bookings_not_canceled</td>
      <td>Total number of previous non-cancelled bookings</td>
    </tr>
    <tr>
      <td>reserved_room_type</td>
      <td>Type of room reserved by the customer</td>
    </tr>
    <tr>
      <td>assigned_room_type</td>
      <td>Type of room assigned to the customer</td>
    </tr>
    <tr>
      <td>booking_changes</td>
      <td>Total changes made to booking</td>
    </tr>
    <tr>
      <td>deposit_type</td>
      <td>Type of deposit(No deposit/ Refundable/ Not refundable)</td>
    </tr>
    <tr>
      <td>agent</td>
      <td>Booking ID of agent</td>
    </tr>
    <tr>
      <td>company</td>
      <td>Booking ID of company</td>
    </tr>
    <tr>
    <td>days_in_waiting_list</td>
    <td>Number of days in waiting list</td>
  </tr>
  <tr>
    <td>customer_type</td>
    <td>Type of customer(Transient, Group,Contract, Transient-Party)</td>
  </tr>
  <tr>
    <td>adr</td>
    <td>Average daily rate</td>
  </tr>
  <tr>
    <td>required_car_parking_spaces</td>
    <td>Total number of car parking required by customer</td>
  </tr>
  <tr>
    <td>total_of_special_requests</td>
    <td>Total number of additional special requirements</td>
  </tr>
  <tr>
    <td>reservation_status</td>
    <td>Status of reservation, if customer (Check-Out, Cancelled, No-Show)</td>
  </tr>
  <tr>
    <td>reservation_status_date</td>
    <td>Date of specific reservation status</td>
  </tr>
  </table>
  
## Project Summary

The Hotel Booking Analysis project aimed to conduct an exploratory data analysis(EDA) on hotel booking data to identify patterns and insights that could help hotel managers make informed decisions. The project utilized data of two hotels - City hotel and Resort hotel - over a period of three years (2015, 2016 and 2017). The data included information on bookings, cancellations, hotel type, room type, number of guests, duration of stay, arrival date, month, country, etc.

The project began loading the data and perform data cleaning, which involved removing duplicates, missing values, outliers and changing data type of required variables. New columns were added accordingly. The cleaned data was then analysed using visualization tools. The charts used for visualization were pie chart, bar chart, line plot, histogram, box plot, kernel density estimate (KDE plot), heat map and pair plot. NumPy and Pandas libraries were used for data wrangling and feature engineering. Matplotlib and seaborn libraries were used for visualization of patterns and trends.

One of the main objectives of this analysis was to identify patterns and trends in hotel booking behaviour. The exploratory analyses included basic summary statistics, such as mean, median, and mode, as well as more advanced visualizations such as histograms, scatterplots, and box plots. To accomplish this, we examined various aspects of the booking process, such as the most popular hotels, booking rates by month, booking channels, room types, distribution of booking cancellations and the reasons for cancellations.

The analysis revealed several insights that could help hotel managers improve their operations and customer service. For example, the data showed that the highest cancellation rate occurred for bookings made through TA/TO, which suggests that hotels may need to reconsider their partnerships with these agencies. The data also showed that the average daily rate was higher for the city hotels. The analysis showed that customers tend to book hotels further in advance for longer stays, suggesting that hotels could benefit from offering early bird discounts for longer stays. Additionally, the analysis revealed that certain types of customers are more likely to cancel their bookings, suggesting that hotels could benefit from offering more flexible cancellation policies for these customers.

A correlation analysis was conducted to identify any relationships between different variables in the dataset, such as the relationship between total guests and average daily rate (ADR). The pair plot was used to plot scatter plot between different variables like previous cancellations, ADR, repeated guest or first visit.

In conclusion, the Hotel Booking Analysis project was successful in conducting an exploratory analysis of hotel booking data to identify patterns and insights that could inform decision-making for hotel managers. The insights gained from this project could help hotels improve their operations and enhance customer satisfaction.
