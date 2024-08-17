# Medicon_dose_testing

Medicon, a pharmaceutical company, has manufactured the sixth batch (40,000 units) of COVID-19 vaccine doses. **This vaccine was clinically tested last quarter and around 200,000 doses have already been given to people in five batches.**

Now, the sixth batch of doses needs to be tested for their **time of effect** (measured as the **time taken for the dose to be absorbed in the body for its COVID-19 preventative effects**, such as antibody creation, to manifest), as well as for **quality assurance** (which tells you whether the dose will be able to do a satisfactory job or not).

You are working with the quality assurance team of Medicon and want to understand the quality of the sixth batch so that the company can plan for the next batch of doses. 

**Note:** Please note that this is not a clinical trial, the vaccine has already cleared clinical trials. This test is to ensure the quality and effectiveness of the sixth batch.


## **Problem Statement** 

The previous analysis found that a dose is ten times more likely to produce a satisfactory result than not.

<br>

**Note:** Here, a satisfactory job for the vaccine means that the dose **has successfully prevented COVID-19** - which is assumed to have taken place if the person does not show any symptoms or side effects after 14 days have passed since the vaccine dose was administered.


<br>

Q1. The quality assurance team has collected 100 volunteers who were ready for the trial of this new batch, and they have given one dose to each volunteer. Help the team answer the following questions:


a) **Plot the probability distribution** for the number of unsatisfactory doses.

b) What is the probability that **exactly 3 doses will not be able to do a satisfactory job**?

c) What is the probability that **at most 3 doses will not do a satisfactory job** out of 100 selected?


<br>

Q2. The New York city administration wants to buy 200 doses for Health care workers who were COVID-Positive. They have contacted the company and requested 200 doses. What is the probability that **at least 30 doses will not do a satisfactory job** out of 200 doses?

<br>

Q3. The quality assurance team wants to analyze the **time of effect for doses**. So, they collected the 50 volunteers with the help of the city administration and gave one dose to each volunteer. Data for these 50 doses are in the 'doses.csv' file. Based on this sample, answer the following questions:

a) What is the probability that the time of effect is **less than 11.5 hours**?

b) What is the **90th percentile of time of effect for the doses**?

c) For the effectiveness test of the vaccine, estimate the range in which **the population mean (time of effect) will lie with a 95% confidence level**.
