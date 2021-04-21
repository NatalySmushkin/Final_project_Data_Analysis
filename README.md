# Telecom: Identifying Ineffective Operators

A virtual telephony service is developing a new function that will give supervisors information on the least effective operators. An operator is considered ineffective if they have a large number of missed incoming calls (internal and external) and a long waiting time for incoming calls. Moreover, if an operator is supposed to make outgoing calls, a small number of them is also a sign of ineffectiveness.

#### Goal

Identify ineffective operators based on:

* A large number of missed incoming calls (internal and external).
* A long waiting time for incoming calls.
* A small number of outgoing calls.

#### Table of contents:

* Open the data files and read the general information
   
* Prepare the data for analysis

    * Check for missing values
    * Replace\delete missing values
    * Check for duplicate values
    * Remove duplicates
    * Check type correspondence
    * Convert types if needed

* EDA

    * Study distribution of data
    * Find outliers 

* Identifying ineffective operators

    * Determine the threshold after which the number of missed calls will be considered too high
    * Determine the threshold after which the waiting time will be considered too long
    * Determine the threshold after which the number of outgoing calls will be considered too small

* Test hypothesis
    
    * If there is statistically significant difference in average waiting time between effective and ineffective operators

* Conclusions

Link to presentation: https://docs.google.com/presentation/d/1NYwhVUyjQnjgwyRLGPr3tmdhDxrAaYl5qbqKdSwlGQM/edit?usp=sharing

Link to Tableau dashbord: https://public.tableau.com/profile/nataliy.smushkin#!/vizhome/CallMeMaybe_16178217776690/Dashboard1
