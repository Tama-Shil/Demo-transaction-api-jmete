# Demo-Transaction-API-Jmeter

## Problem Statement Scenario
Based on following scenario, create a JMX file. No need to create negative testing. Just create the positive test case based on this flow. (30)
1. Admin creates an agent and a customer
2. Deposit 2000 tk to agent from system account (fromAc: SYSTEM)
3. Deposit 1000 tk to customer from agent account
4. Check balance from customer account
5. Withdraw 500 tk from customer account
6. Payment 200 tk from customer account (Create any merchant acc or search any merchant for payment)

**User documentation:**
You will get the user API URL, endpoint, header info and demo data from here:
_https://documenter.getpostman.com/view/1844288/2s9YeABaGo_

**Transaction documentation:**
You will get the transaction API URL, endpoint, header info and demo data from here:
_https://documenter.getpostman.com/view/1844288/2s9YeABaGp_

## Prerequisites:
- jdk (Latest LTS) with envirmonment setup
- Apache Jmeter with envirmonment setup

## Technology used:
- JMeter

## How to Run

- Clone the project
- Save the DmoneyAPI.jmx file into a folder in the bin folder of Jmeter.
- Open the ApacheJmeter Application and open DmoneyAPI.jmx file
- Now Run the Project

## Generate Report 
- Go to the command prompt from the DmoneyAPI.jmx location
- Write the command ```` $ jmeter -n -t Jmx_Dmoney_Api.jmx -l Jmx_Dmoney_Api.csv -e -o Reports ````
- The Report folder contains the index html file containing the report

## Report Screenshot:
![image](https://github.com/user-attachments/assets/96db7c6a-0a64-47b3-b4ca-7e79f7b5a972)

