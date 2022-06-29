## JMeter Assignment 01

#### **Question**

- Find out the actual TPS for if 10000 user can give load within 1 hour **Expected load:** 10000 user, per hour.
- **Actual load:** what TPS? Breakdown the expected TPS in excel sheet and find out the actual TPS.
- For 60s, 300s and 600s load, add Jmeter UI screenshot and for 900s generate html report and take screenshot.

##### **Solved**

- #### [**Excel and Word Report**](https://github.com/monirQA/Assignment-3-Book-API-Load-Test/tree/master/Resources)

#### **Load Test Strategy**

- [Server](https://demoqa.com/BookStore/v1/Books)

| ![TPS Report](./images/load-test-strategy.PNG) |
| :------------------------------------: |
|              _Actual TPS_              |

#### **JMeter Summary Report**

- 166 users for 60 seconds

| ![Test Case 1](./images/load-status-60s.PNG) |
| :----------------------------------: |
|         _60 sec, 166 users_          |

- 833 users for 300 seconds

| ![Test Case 2](./images/load-status-300s.PNG) |
| :----------------------------------: |
|         _300 sec, 833 users_         |

- 1666 users for 600 seconds

| ![Test Case 3](./images/load-status-600s.PNG)|
| :----------------------------------: |
|        _600 sec, 1666 users_         |

- 2500 users for 900 seconds (part-1)

| ![Test Case 4](./images/load-status-900s%20part1.PNG) |
| :----------------------------------: |
|        _900 sec, 2500 users_         |

- 2500 users for 900 seconds

| ![Test Case 5](./images/load-status-900s%20part2.PNG) |
| :-------------------------------------: |
|          _900 sec, 2500 users_          |

- 2500 users for 900 seconds (part-2)

| ![Test Summary Report](./images/Apache%20JMeter%20Dashboard.png) |
| :------------------------------------------: |
|               _Summary Report_               |
