# Determining a promising tariff for a telecom company

### Data
Data from 500 Megaline users: who they are, where they are from, what tariff they use, how many calls and messages each person sent in 2018.

**Description of data:**

Users table (user information):
- user_id — unique user identifier
- first_name — user name
- last_name — user’s last name
- age — user age (years)
- reg_date — tariff connection date (day, month, year)
- churn_date — date of termination of using the tariff (if the value is omitted, then the tariff was still in effect at the time of data upload)
- city — user’s city of residence
- tariff — name of the tariff plan

Calls table (information about calls):
- id — unique call number
- call_date — call date
- duration — duration of the call in minutes
- user_id — identifier of the user who made the call

Messages table (message information):
- id — unique message number
- message_date — message date
- user_id — identifier of the user who sent the message

Internet table (information about Internet sessions):
- id — unique session number
- mb_used — the amount of Internet traffic spent per session (in megabytes)
- session_date — date of the Internet session
- user_id — user identifier
  
Tariffs table (information about tariffs):
- tariff_name — tariff name
- rub_monthly_fee — monthly subscription fee in rubles
- minutes_included — number of conversation minutes per month included in the subscription fee
- messages_included — number of messages per month included in the subscription fee
- mb_per_month_included — the amount of Internet traffic included in the subscription fee (in megabytes)
- rub_per_minute — the cost of a minute of conversation above the tariff package (for example, if the tariff includes 100 minutes of conversation per month, then a fee will be charged from 101 minutes)
- rub_per_message — cost of sending a message in excess of the tariff package
- rub_per_gb — the cost of an additional gigabyte of Internet traffic above the tariff package (1 gigabyte = 1024 megabytes)

### The goal of the project

- Make a preliminary analysis of tariffs on a small sample of clients.
- Analyze customer behavior and draw a conclusion - which tariff is better.

### Completed tasks

- Casting data to the desired type
- Checking for omissions and duplicates/processing omissions and duplicates
- Checking for anomalies/processing anomalies
- Data analysis and visualization
- Testing hypotheses about the difference in average revenues of users of two tariffs using t-test

The project is finished.

### Key takeaways:

- Having tested the hypothesis about the equality of the average revenue values ​​of the two tariffs, we came to the conclusion that the averages are not equal.
- Since the average price for the Ultra tariff is higher than for the Smart tariff, this means that the Ultra tariff brings in more revenue and is more profitable.
- We also tested the hypothesis that the average revenue of Moscow users is approximately equal to the average revenue of users from other regions. This hypothesis was accepted.

### Libraries used

Pandas, numpy, matplotlib, seaborn, math, scipy
