# -Provide-Insights-to-Chief-of-Operations-in-Transportation-Domain

*****
##                                         Business Request

### Business Request - 1: City-Level Fare and Trip Summary Report
Generate a report that displays the total trips, average fare per km, average fare per trip, and
the percentage contribution of each city’s trips to the overall trips. This report will help in
assessing trip volume, pricing efficiency, and each city’s contribution to the overall trip count.

Fields:

city_name

total_trips

avg_fare_per_km

avg_fare_per_trip

%_contribution_to_total_trips

![Screenshot 2024-11-15 194051](https://github.com/user-attachments/assets/a8934505-aa6e-4c77-8942-8556cf55f4b7)
![Screenshot 2024-11-15 194102](https://github.com/user-attachments/assets/48975dd4-4dbb-44f1-9ec7-9de96bb7ac78)

*****

### Business Request - 2: Monthly City-Level Trips Target Performance Report
Generate a report that evaluates the target performance for trips at the monthly and city
level. For each city and month, compare the actual total trips with the target trips and
categorise the performance as follows:

If actual trips are greater than target trips, mark it as "Above Target".

If actual trips are less than or equal to target trips, mark it as "Below Target".

Additionally, calculate the % difference between actual and target trips to quantify the
performance gap.

Fields:

City_name

month_name

actual_trips

target_trips

performance_status

%_difference

![Screenshot 2024-11-15 200039](https://github.com/user-attachments/assets/8ac0901b-6c32-47d7-95f0-6cba66b675b6)
![Screenshot 2024-11-15 200101](https://github.com/user-attachments/assets/de1786bb-8b83-4bcd-b0a5-c0fdff64554d)
![Screenshot 2024-11-15 200130](https://github.com/user-attachments/assets/ede481af-40ab-4fb3-9275-ab337cde3e18)


![Screenshot 2024-11-15 200546](https://github.com/user-attachments/assets/d5580963-7f07-4dae-b4fc-9393668ae090)
![Screenshot 2024-11-15 200627](https://github.com/user-attachments/assets/e770a51b-9b6b-42b2-a51d-2ab93dc9186d)
![Screenshot 2024-11-15 200652](https://github.com/user-attachments/assets/c875aaf9-7546-492a-9d6e-f8ed0f866ff6)
![Screenshot 2024-11-15 200702](https://github.com/user-attachments/assets/77a1031a-4518-473a-a6d9-c38921d14467)
![Screenshot 2024-11-15 200715](https://github.com/user-attachments/assets/85e63e0e-30d8-4137-a048-3f0e45215884)

*************


### Business Request - 3: City-Level Repeat Passenger Trip Frequency Report
Generate a report that shows the percentage distribution of repeat passengers by the
number of trips they have taken in each city. Calculate the percentage of repeat passengers
who took 2 trips, 3 trips, and so on, up to 10 trips.

Each column should represent a trip count category, displaying the percentage of repeat
passengers who fall into that category out of the total repeat passengers for that city.
This report will help identify cities with high repeat trip frequency, which can indicate strong
customer loyalty or frequent usage patterns.
e Fields: city_name, 2-Trips, 3-Trips, 4-Trips, 5-Trips, 6-Trips, 7-Trips, 8-Trips, 9-Trips,
10-Trips

![Screenshot 2024-11-15 224229](https://github.com/user-attachments/assets/6b37eb5e-2da5-459d-ace9-e5623ab9f316)
![Screenshot 2024-11-15 224251](https://github.com/user-attachments/assets/ce4295d8-eb36-4e72-a2fe-03b34e83999e)
![Screenshot 2024-11-15 224305](https://github.com/user-attachments/assets/4c857929-5c53-459f-a64a-1204673a5ed3)
![Screenshot 2024-11-15 224319](https://github.com/user-attachments/assets/50b013a1-7569-4ebf-a7ab-91f89c859961)
![Screenshot 2024-11-15 224334](https://github.com/user-attachments/assets/0f01a674-642e-4014-a00f-e202d796fc62)

**********


### Business Request - 4: Identify Cities with Highest and Lowest Total New
Passengers
Generate a report that calculates the total new passengers for each city and ranks them
based on this value. Identify the top 3 cities with the highest number of new passengers as
well as the bottom 3 cities with the lowest number of new passengers, categorising them as
"Top 3" or "Bottom 3" accordingly.

Fields

* city_name

* total_new_passengers

* city_category ("Top 3" or "Bottom 3")



![Screenshot 2024-11-15 231328](https://github.com/user-attachments/assets/1a1c3e8a-b67a-4d28-b601-3a689132cffa)
![Screenshot 2024-11-15 231337](https://github.com/user-attachments/assets/916267b3-e94e-48f8-8ec0-e69757b6b078)
![Screenshot 2024-11-15 231348](https://github.com/user-attachments/assets/a6e5ded3-e1c4-4455-a59b-5d601639cf50)
![Screenshot 2024-11-15 231413](https://github.com/user-attachments/assets/036528a0-c671-48e6-b619-f6e826aed83d)
![Screenshot 2024-11-15 231422](https://github.com/user-attachments/assets/ea32b4b7-8174-472c-a3aa-4f3a7ed793a9)
![Screenshot 2024-11-15 231430](https://github.com/user-attachments/assets/04ce01e7-bf39-44ba-aa84-a128182b3367)




### Business Request - 5: Identify Month with Highest Revenue for Each City
Generate a report that identifies the month with the highest revenue for each city. For each
city, display the month_name, the revenue amount for that month, and the percentage
contribution of that month’s revenue to the city’s total revenue.
Fields

* city_name
* highest_revenue_month
* revenue
* percentage_contribution (%)


![Screenshot 2024-11-15 233944](https://github.com/user-attachments/assets/d5952c84-7510-4a2b-9e3e-9422a6fb96c2)
![Screenshot 2024-11-15 234000](https://github.com/user-attachments/assets/05035f2c-e942-47eb-bf92-2901b4127a2f)
![Screenshot 2024-11-15 234008](https://github.com/user-attachments/assets/fdaf9370-3ef1-4185-954b-a202440d3bf3)
![Screenshot 2024-11-15 234045](https://github.com/user-attachments/assets/77be190d-7dc0-462a-b52a-70c2f7dd4b8c)


### Business Request - 6: Repeat Passenger Rate Analysis
Generate a report that calculates two metrics:
1. Monthly Repeat Passenger Rate: Calculate the repeat passenger rate for each city
and month by comparing the number of repeat passengers to the total passengers.
2. City-wide Repeat Passenger Rate: Calculate the overall repeat passenger rate for
each city, considering all passengers across months.
These metrics will provide insights into monthly repeat trends as well as the overall repeat
behaviour for each city.
Fields:
city_name
month
total_passengers
repeat_passengers
monthly_repeat_passenger_rate (%): Repeat passenger rate at the city and
month level
e city_repeat_passenger_rate (%): Overall repeat passenger rate for each city,
aggregated across months

![Screenshot 2024-11-18 094553](https://github.com/user-attachments/assets/35625e13-4406-4521-a3c8-71e46f09d44c)
![Screenshot 2024-11-18 094843](https://github.com/user-attachments/assets/10bc4202-02f7-4ee5-a364-fbe48038de19)

![Screenshot 2024-11-18 094613](https://github.com/user-attachments/assets/ee64547a-a036-4e2e-a45e-6e436b3c66b5)



