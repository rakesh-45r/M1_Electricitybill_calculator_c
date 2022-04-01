# Electricitybill Calculator

# Introduction

The Electricity Bill calculator project is the application based mini project,which is used to predict the electricity bill of next month by taking input of appliance or load used. The tool used for writing the code in this project is visual studio code. This project has multi file and multiplatform approach (Linux and Windows).

The amount of money framed by the supplier for the supply of electrical energy to various types of consumers is calculated.The bill covers the total cost of producing and supplying electrical energy and in addition to reasonable cost.

The electricity bill depends on the following factors : 1) Type of load 2) Time at which load is required 3) The amount of energy used.
The actual bill that the consumer pay depends on the consumption of the eletricity. The industrial consumers pay more bill because they use more power for long times than the domestic consumers.

## Research
### Objective
The goal of this project is to assess to the People who don’t have technical knowledge of calculating electricity bill can use this application to predict electricity bill of upcoming months, however, the defining features of an electricity bill calculator include

- power rating of all loads
- total load calculation
- unit consumed per day
- units consumed per month

In addition, high-end electricity bill calculators generally include:

- bill calculation based on units consumed.

**Cost Vs Timeline**
**
` `This is the plot of cost of the calculators in ($ ) and time in  years

![Aspose Words 088b8439-ce94-4b00-aac5-64487bb801e5 001](https://user-images.githubusercontent.com/89764315/132320020-ab527da5-1522-4eb4-b645-75367eb9363a.png)

**Defining System:** 

Design and testing operations of electricity bill calculator using unit testing algorithm.


**SWOT analysis:**

**Strengths:** Innovative, User-friendly.

**Weakness**: Cost of calculator increases as features added in the calculator increase.

**Opportunities**: We know that we mostly use pen and paper for calculation. So tech based market always attracts the youth.

**Threats**: Slower growth in an innovation always threat for the company in this dynamic world.

**4’W and 1’H**

**What:**  Electricity bill calculator**     

**Who:** .Consumers of different types will consume the electricity.

**Where:** School, Science, domestic, industries, Technology.It is used all over the world.

**When:** Need for calculation.It can be used everytime and world is nothing without electrical power.

**How:** Calculates the user input as number of loads and gives the output.From conventional energy sources the energy is converted into useful form of electrical energy and it is generated, transmitted and distributed to consumers. And hence along with the units multiplied with rate of charge,the maintenance nothing but fixed and consumer charges are also added.  

**Detail Requirements:**

**High Level Requirements:**
Units will be recorded from the difference of prev reading and current reading.

| ID   | Description                                 | Category  | Status      |
| -----|:-------------------------------------------:|:---------:|:-----------:|
| HR01 | User can able to calculate Electricity bill | Technical | IMPLEMENTED |
| HR02 | User can able to know power rating of all loads| Technical | IMPLEMENTED |
| HR03 | User can be able to know total unit consumed| Technical | IMPLEMENTED |
| HR04 | User can be able to know cost of electricity| Technical | IMPLEMENTED |

## Low Level Requirements
| ID    | Description                                                                 | HLR ID | Status (Implemented/Future) |
| ------|:---------------------------------------------------------------------------:| ------:|----------------------------:|
| LR01  | select Group                                                                | HR01   | IMPLEMENTED |
| LR02  | The group will be selected like A or B or C                                 | HR01   | IMPLEMENTED |
| LR03  | If it not belongs to first group it will be directly switch into other group| HR01   | IMPLEMENTED |
| LR04  | After the selected The rate of charge belongs to that particular group will be multiplied with no. of units to get energy charges.  | HR02   | IMPLEMENTED |
| LR05  | The bill amount will be calculated by adding energy charges to fixed charges, customer charges and electrical duty charges.         | HR03   | IMPLEMENTED |
| LR06  | And hence the total amount will be noted                                                             | HR01 HR02   | IMPLEMENTED |
