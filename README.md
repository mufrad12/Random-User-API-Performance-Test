# Random User API Performance Test

## Technology and Tool Used
- Apache JMeter
- Java

## Scenerio
Find out the actual TPS for if 120000 user can give load for 12 hour. \
Perform load test on this URL: https://random-data-api.com/api/v2/users
1. You have to find out if the expected TPS (Transaction Per/Second) meet the above requirement.
Breakdown the expected TPS in excel sheet and find out the actual TPS

2. Create another excel sheet where you will try to find out the bottleneck/stress test point. (At which point the system starts to show 1% error)

## How to run this project
- Clone this project
- Run the .jmx file on jmeter

## Prerequisite
- Java & Jmeter must be installed


## Load & Stress Test Strategy Excel File: 
https://docs.google.com/spreadsheets/d/1A5EIL_-chho5nfFFR62-I1K54wNIDuvLtitAcyKPPXI/edit?usp=sharing

## Screenshot of Load Test Strategy Report
![TPS](https://user-images.githubusercontent.com/58912515/215345866-d33db483-1875-4e47-9ee1-91b0333dd401.png)


## Screenshot of Stress Test Strategy Report
![stress](https://user-images.githubusercontent.com/58912515/215345865-1883f1bd-a531-4a37-83ec-88bedb80f94f.png)

## Screenshot of Jmeter Summary Report for 60 sec TPS
![60 sec tps](https://user-images.githubusercontent.com/58912515/215345891-0adc505b-4e28-4152-8974-8a51276ffbce.png)
