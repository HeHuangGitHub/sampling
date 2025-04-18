# Assignment: Questionnaire Design and Sample Evaluation

## Requirements

The goal of this assignment is to practice developing and evaluating sampling materials.

### Part A - Survey Design:

Select one of the scenarios below and design a survey to meet the need(s) outlined in the prompt.

1.	In two to three sentences, describe the purpose of your survey
2.	Describe your target population, sampling frame, sampling units, and overall sampling strategy.
3.	Write a 5-10 question survey to address your chosen scenario below.

##### Scenarios
1.	You work in the Human Resources Department at a large tech company. Over the past few months, the company has been experiencing a high turnover rate across many of its departments, specifically within the entry- and lower-level positions. The company wishes to understand why this turnover is happening, and what changes need to occur to improve employee satisfaction.
2.	You work for a Canadian national political party during a federal election. Throughout the campaign period, your party has seen relatively high approval ratings, but an opposing party is also polling favorably and may still have a chance to win the election. You are one month away from the election and you want to understand what voters want from your party and its leader in order to maintain your lead and eventually win the election.
3.	You are a student researcher in the sociology department at the University of Toronto. You are working on a research project that concerns the relationship between music taste and age. This involves both comparisons between different people of different ages and comparisons of the same individual at different ages during their lifetime. You wish to understand to what extent age influences music taste, specifically as it relates to perceptions of popular music. Your results will be written into an academic paper that you hope to publish.

### Part B - Survey Evaluation:

For the **Canadian General Social Survey on Giving, Volunteering, and Participating, 2018 (cycle 33)**, conducted by Statistics Canada find any and all available documentation for the data gathered and identify and describe the survey features indicated below.

1. Sample type
2. Sample size
3. Target population
4. Sampling frame
5. Survey mode(s) 
6. Timeline
7. Response rate
8. Weights
9. Data processing
10. Cleaning, imputation, etc
11. Sources of error
12. Limitations, known biases, etc
13. Link to documentation and any additional sources used


# Your Changes

## Part A - Survey Design: 

The number of your chosen topic: `#` 1

Describe the purpose of your survey:
```
The survey is trying to find out the reasons why the employees are leaving many departments. The survey questions try to pinpoint the areas that cause dissatisfaction from the employees so that the company can improve.
```

Describe your target population, sampling frame, sampling units, and observational units:
```
Target population: the employees of the company
Sampling frame: a list of all employee emails
Sampling units: individual employees
Overall sampling strategy: stratified sampling to ensure employees from every department were represented. This way, we can compare the responses from departments with high versus low turnover rates.
```

Your 5-10 question survey:
```
1. How long have you been with the company?
   - Less than 6 months  
   - 6 months to 1 year  
   - 1–2 years  
   - More than 2 years  

2. How satisfied are you with your current role? (Scale: 1–5, where 1 = Very Dissatisfied, 5 = Very Satisfied)

3. What are the top reasons you would consider leaving the company?
   - Lack of career growth opportunities  
   - Compensation or benefits not compelling 
   - Workload/stress levels  
   - Poor management
   - Lack of work-life balance 
   - Other (please specify): __

4. What changes would most improve your job satisfaction? (Open-ended)

5. Do you feel you have clear opportunities for career advancement within the company?
   - Yes, with clear pathways 
   - Somewhat, but not well-defined  
   - No, advancement seems unlikely  
   - Unsure 

6. Would you recommend this company as a good place to work to friends or peers? Why or why not? (Open-ended)
```

## Part B - Survey Evaluation:

Identify and describe survey features:

```
1. Sample type

Each record in the survey frame was assigned to a stratum within its province. A simple random sample without replacement of records was next selected in each stratum.

2. Sample size

The target sample size was 20,000, while the actual number of respondents was 16,149.

3. Target population

The target population for the survey included all persons 15 years of age and older in Canada, excluding:
1) Residents of the Yukon, Northwest Territories, and Nunavut;
2) Full-time residents of institutions.

4. Sampling frame

The survey frame was created using two different components:
1) Lists of telephone numbers in use (both landline and cellular) available to Statistics Canada from various sources (Telephone companies, Census of population, etc.);
2) The Address Register (AR): List of all dwellings within the ten provinces.

5. Survey mode(s)
Both telephone and Internet modes.

6. Timeline
The reference period was the 12 months preceding the interview. Interviews were conducted from September 4th to December 28th, 2018.

7. Response rate
The overall response rate was 41.9%.

8. Weights
Several weight adjustments were performed depending on the province, volunteer status, stratum, age and sex of the respondent

9. Data processing
The survey responses were processed into table form for data analysis. The write-in response were coded into existing categories. Duplicates and out-of-scope responses were eliminated.

10. Cleaning, imputation, etc

Most imputations were made using donor records selected through a score function. Certain characteristics on each record with item or partial non-response (also called a recipient record) were compared with the characteristics on all donor records. When a characteristic was the same on the donor record and the recipient record, the donor’s score increased. The donor record with the highest score was deemed the “nearest” donor and was chosen to fill in the missing information of the non-respondent.

11. Sources of error
The sources of errors came from sampling errors and non-sampling errors.
1) The sampling errors are the difference between the estimates obtained from the sample and the results from a complete count taken under similar conditions, which are unavoidable but can be estimated by the standard error.
2) The non-sampling errors can occur from non-response on survey results, misunderstanding instructions by the interviewers, errors from answering questions, and errors introduced in the processing and tabulation of the data.


12. Limitations, known biases, etc
1) The introduction of an electronic questionnaire had an impact on the estimations. So, the GSS GVP 2018 cannot be compared with previous years.
2) The high non-response rate was the major source of non-sampling errors, which may resulted in biases.

13. Link to documentation and any additional sources used
https://www150.statcan.gc.ca/n1/pub/45-25-0001/cat5/c33_2018.zip

```

## Rubric

-	All required components are present and complete **Complete / Incomplete**
-	Choice of sampling strategy for Part A is justified and related to survey purpose **Complete / Incomplete**
-	Information for Part B is complete and correct **Complete / Incomplete**

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 18/04/2025`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (a2_survey_design_and_evaluation.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/sampling/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [X] Create a branch called `assignment-2`.
- [X] Ensure that the repository is public.
- [X] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [X] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via the help channel in Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
