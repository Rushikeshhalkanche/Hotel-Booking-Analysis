# Hotel-Booking-Analysis
The project contains the real world data record of hotel bookings of a city and a resort hotel containing details like bookings, cancellations, guest details etc. from 2015 to 2017. In this project we are going to analyze Hotel Booking Data in order to find out valuable insights and give suggestions to increase revenue of hotels.

Programming Language : Python
Libraries used : Pandas, Numpy, Matplotlib, Seaborn
NoteBook : Google Colab
Dataset Source : Provided by Almabetter themself

Objective
We are provided with a hotel bookings dataset.
The main purpose of this study is to perform EDA on the given dataset and draw useful conclusions about the trends in hotel bookings and how factors that control hotel bookings influence each other.

Dataset
We are given a hotel bookings dataset. This dataset contains booking information for a city hotel and a resort hotel. It contains the following features.

- hotel: Name of hotel ( City or Resort)
- is_canceled: Whether the booking is canceled or not (0 for no canceled and 1 for canceled)
- lead_time: time (in days) between booking transaction and actual arrival.
- arrival_date_year: Year of arrival
- arrival_date_month: month of arrival
- arrival_date_week_number: week number of arrival date.
- arrival_date_day_of_month: Day of month of arrival date
- stays_in_weekend_nights: No. of weekend nights spent in a hotel
- stays_in_week_nights: No. of weeknights spent in a hotel
- adults: No. of adults in single booking record.
- children: No. of children in single booking record.
- babies: No. of babies in single booking record. 
- meal: Type of meal chosen 
- country: Country of origin of customers (as mentioned by them)
- market_segment: What segment via booking was made and for what purpose.
- distribution_channel: Via which medium booking was made.
- is_repeated_guest: Whether the customer has made any booking before(0 for No and 1 for Yes)
- previous_cancellations: No. of previous canceled bookings.
- previous_bookings_not_canceled: No. of previous non-canceled bookings.
- reserved_room_type: Room type reserved by a customer.
- assigned_room_type: Room type assigned to the customer.
- booking_changes: No. of booking changes done by customers
- deposit_type: Type of deposit at the time of making a booking (No deposit/ Refundable/ No refund)
- agent: Id of agent for booking
- company: Id of the company making a booking
- days_in_waiting_list: No. of days on waiting list.
- customer_type: Type of customer(Transient, Group, etc.)
- adr: Average Daily rate.
- required_car_parking_spaces: No. of car parking asked in booking
- total_of_special_requests: total no. of special request.
- reservation_status: Whether a customer has checked out or canceled,or not showed 
- reservation_status_date: Date of making reservation status.

Total number of rows in data: 119390
Total number of columns: 32

Data Cleaning and Feature Engineering
(1) Handling null values
(2) Removing Duplicate rows
(3) Converting columns to appropriate data types

Exploratory Data Analysis
Performed EDA and tried answering the following questions:

1.  What is percentage of bookings in each hotel?
2.  Which hotel has more no of bookings?
3.  Booking by years.
4.  Which month have most people prefer to visit.
5.  Which is the most common channel for booking hotels?
6.  From Where the most guests are coming ?
7.  Waiting time
8.  What is reservation status of both the hotels?
9.  Is thier any Special request given by the customer to hotels?
10.  Cancellation rates in both the hotels.
11.  What is the percentage of most repeated guests?

 Mainly performed using Matplotlib and Seaborn library and the following graph and plots had been used:

  Bar Plot.
  Scatter Plot.
  Pie Chart.
  Line Plot.
  Heatmap.
  Box Plot.

Analysis:
Performed analysis and made following conclusions:

 1.) 61% bookings are for City hotel and 39% bookings are for Resort hotel, therefore City Hotel is busier than Resort hotel. 
 2.) July- August are the most busier and profitable months for both of hotels.  
 3.) Most popular meal type is BB(Bed and Breakfast).
 4.) Most of the guests came from european countries, with highest number of guests from Portugal.
 5.) Agent no. 9 has made most no. of bookings.
 6.) Most demanded room type is A, but better average daily rate generating rooms H, G and C. Hotels should increase the no. of room types A and H to maximise revenue.
 7.) Most common stay length is less than 4 days and generally people prefer City hotel for short stay, but for long stays, Resort Hotel is preferred.
 8.) Guests use different channels for making bookings out of which most preferred way is TA/TO. 
 9.) Overall average daily rate of City hotel is slightly higher than Resort hotel and no. of bookings of City hotel is also higher than Resort hotel. Hence, City hotel is makes more revenue.
 10.) Cancelation rate is higher in city hotel. With lead time more than 100 there is more possibility of cancellation.
 11.) Both hotels have very small percentage that customer will repeat.
 12.) Arrivals in hotels increases at weekends and also the average daily rate tends to go up as month ends. 
 13.) Moslty bookings are done by couples(bookings have two adults.)

 Conclusion
The majority of guests come from western europe countries.We should spend a significant amount of our budget on those area.
Around 61% bookings are for City hotel and 39% bookings are for Resort hotel, therefore City Hotel is busier than Resort hotel.Majority of the hotels booked are city hotel. Definitely need to spend the most targeting fund on those hotel.
We should also target months between May to Aug. Those are peak months due to the summer period.
Given that we do not have repeated guests, we should target our advertisement on guests to increase returning guests.
Most common stay length is less than 4 days and generally people prefer City hotel for short stay, but for long stays, Resort Hotel is preferred.
November,Descember, February And January are the months which has less booking so in this perios you can get rooms with less average daily rate. And Avoid most busiest months for hotels (May,June,July,August).
