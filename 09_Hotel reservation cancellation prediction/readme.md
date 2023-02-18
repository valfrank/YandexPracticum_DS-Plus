# Hotel reservation cancellation prediction

## Project description

The hotel chain has added the ability to book a room without prepayment on its website. However, if the client canceled the booking, then the company suffered losses.
We need to develop a model that predicts сancel reservation. If the model shows that the booking will be cancelled, then the client is asked to make a deposit. The deposit is 80% of the cost of the room for one day and the cost of one-time cleaning. The money will be debited from the client's account if he still cancels the reservation. Development costs should be less than the revenue that the system will bring to the company.

**Aim** - build a model to predict сancel reservation with the greatest business profit.


## Data

**The hotel_train and hotel_test tables contain the same columns:**
- id — record number;
- adults - the number of adult guests;
- arrival_date_year — year of arrival;
- arrival_date_month — month of arrival;
- arrival_date_week_number — arrival week;
- arrival_date_day_of_month — day of arrival;
- babies - number of babies;
- booking_changes — number of order parameter changes;
- children - the number of children from 3 to 14 years old;
- country - citizenship of the guest;
- customer_type - customer type:
    + Contract — an agreement with a legal entity;
    + Group — group check-in;
    + Transient - not associated with a contract or a group ride;
    + Transient-party - Not associated with a contract or group stay, but associated with a Transient booking.
- days_in_waiting_list - how many days the order was waiting for confirmation;
- distribution_channel — order distribution channel;
- is_canceled - order cancellation;
- is_repeated_guest - a sign that the guest is booking a room for the second time;
- lead_time - the number of days between the date of booking and the date of arrival;
- meal — order options:
    + SC - no additional options;
    + BB - breakfast included;
    + HB - includes breakfast and lunch;
    + FB - includes breakfast, lunch and dinner.
- previous_bookings_not_canceled — the number of confirmed bookings for the client;
- previous_cancellations - the number of canceled orders from the client;
- required_car_parking_spaces - the need for a place for a car;
- reserved_room_type — reserved room type;
- stays_in_weekend_nights - number of nights during the weekend;
- stays_in_week_nights - number of nights on weekdays;
- total_nights - total number of nights;
- total_of_special_requests - the number of special marks.

## Resume
- Pre-processing and exploratory data analysis
- Estimate the profit of the hotel without the introduction of deposits.
- Train three models and evaluate their quality by cross-validation using Recall-score.
- Estimate the profit that the selected model will bring in a year.
- Describe a customer who is prone to cancel reservation.

## Skills and tools 
- python
- pandas
- mathplotlib
- seaborn
- sklearn
- pipeline
- GridSearchCV
- SMOTE
- sweetviz
