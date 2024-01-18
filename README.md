Personal Small Side EDA Project - Hotel Booking Dataset
Find the dataset and its metadata at this link: https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand
This EDA project is done with Python in the Jupyter Notebook.

Here were the steps taken for the project: 
1. Import the python libraries needed
2. Import the dataset as df
3. Examine dataset and check what needs to be cleaned
4. Remove duplicates, fill NA values, remove redundant columns, make dataset more consistent by ensuring consistent unique values if attribute is categorical
5. Explore and Analyse the dataset

Some questions were asked in order to help understand the dataset better:
- What proportion of bookings are canceled in each hotel, and for each year (if applicable)?
- What was the most frequent lead time at which cancellations occurs?
- What is the average daily transaction rate for each recorded booking across the years for each hotel?

(note: Average daily rate (ADR) is defined by dividing the sum of all lodging transactions by the total number of staying nights)
(note: Lead time is the number of days that elapsed between the entering date of the booking into the PMS and the arrival date)

Essentially, this small EDA project sought to find out the cause for high cancellations across the years for both city and resort hotels.

Through the list of questions, I found out that there were greater cancellations in the year 2016 for City Hotels, and 2016 and 2017 had greater cancellations for Resort Hotels.
Coincidentally, the average daily rate (ADR) was highest for the said year(s) and hotels. This could suggest that the reason for high cancellations for the said years
was due to the high average daily rate. It was shown in the plotted line graph that the average daily rate was highest in the 3rd quarter of 2016 and 2017 for resort hotels, and 
highest in the 1st quarter of 2016 for city hotels. This suggests higher transactions, possibly from a change in season or events in the countries.

As the number of cancelled bookings are closely related to the average daily rate, it is thus important for hotels to then pay more attention to the peak seasons and produce
customer retention policies or new price strategies. In relation to customer retention policy, it was also found that bookings with less than 100 days of lead time (to their arrival)
have a higher chance of cancelling. As such, hotels can pay more attention to the customers with a lead time of less than 100, and create customer retention policies. 
