# Machine Learning Engineer Nanodegree
## Capstone Proposal
Maik Schulte
Feburary 11st, 2019

## Proposal
_(approx. 2-3 pages)_

### Domain Background
_(approx. 1-2 paragraphs)_

Currently I am working as a consultant for SAP software. In the SAP System we do have lots of data and a lot of clerks are working on it. As clerks are very expansive, companies are searching for possibilities to reduce this cost. Automation of manual tasks could be one way to archive this goal.

SAP itself is able to automate a lot of tasks by its own. However, it uses only very little machine learning possibilities. But let me describe the problem in more detail:

### Problem Statement
_(approx. 1 paragraph)_

The SAP module CRM is used for every interaction between customer and company. These interactions need to be performed by employees. Nevertheless, in large companies there are employees specialised for different topics. This means:
department 1: billing
department 2: endurance of products

If a customer request with topic billing is routed to department 2, an employee will read through the customer request. Because he is not able to answer the request he is assigning the ticket to the billing department. This is consuming a lot of time and it could be automated using machine learning.

### Datasets and Inputs
_(approx. 2-3 paragraphs)_

As a dataset I would like to use the popular 20 Newsgroups data set. It is available on http://qwone.com/~jason/20Newsgroups/. It includes around 18.828 news documents. All of these belong to 1 of 20 categories.

Of course, this dataset does not include real customer requests. I want to use this dataset, because it includes a lot of categorized text. And this data should be really similar to categorized customer request.

### Solution Statement
_(approx. 1 paragraph)_

The machine learning model could provide a first guess for the category of the customer request. And save money and time for a company this way.

### Benchmark Model
_(approximately 1-2 paragraphs)_

As a benchmark model, I would like to use Naive Bayes classifier for multinomial models provided in sk learn documentation:
https://scikit-learn.org/0.19/datasets/twenty_newsgroups.html

### Evaluation Metrics
_(approx. 1-2 paragraphs)_

As a benchmark a performance scoring can be used. For example:
proportion of correct classifications,
f1 score,
etc.

### Project Design
_(approx. 1 page)_
I would like proceed as follows:
Please Note: a) b) c) ... show options I would like to use and eventually compare.

1. read & analyse the data
2. create vector from text
  a) using sk learn count vectorizer
  b) using word embeddings
  
3. create a model to predict text category
  a) using sk learn
  b) using deep neural network (is applicable: use cnn or rnn)
  
4. test and visualise the performance
  a) show examples
  b) show the overall performance

-----------

**Before submitting your proposal, ask yourself. . .**

- Does the proposal you have written follow a well-organized structure similar to that of the project template?
- Is each section (particularly **Solution Statement** and **Project Design**) written in a clear, concise and specific fashion? Are there any ambiguous terms or phrases that need clarification?
- Would the intended audience of your project be able to understand your proposal?
- Have you properly proofread your proposal to assure there are minimal grammatical and spelling mistakes?
- Are all the resources used for this project correctly cited and referenced?
