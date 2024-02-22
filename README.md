`sql-project-fc`
## Hello there ✋
There's my final Python and Machine Learning in Data Science bootcamp.

This project is the result of completing a 375-hours **Data Science** bootcamp at the _Future Collars_ training company in Poland.
I used Visual Studio Code as notebook to implement the project.

BTW: I had to remove 25499 removes from loan_data.csv, because because the file exceeded 25MB.
The notebook was made for a file with all data (over 44 MB csv).

Enjoy!

#### Project tasks:
```
Lending Club is a peer-to-peer lending company that connects borrowers with investors through an online platform.
It serves people who need personal loans ranging from $1,000 to $40,000.
Borrowers receive the full amount of their loan minus an origination fee that is paid to the company.
Investors purchase notes secured by personal loans and pay Lending Club a service fee.
Lending Club provides data on all loans originated through its platform during specified periods.
For the purposes of this project, data on loans granted through Lending Club from 2007 to 2011 were used.
Each loan has information about whether it has finally been repaid (Fully Paid or Charged off in the loan_status column).
Your task is to build a classification model that, based on this data,
will predict with a certain accuracy whether a potential borrower will repay his debt under the loan.
The data set includes a file with a description of all variables and the "FICO Score ranged.pdf" file,
which describes in detail the meaning of one of the columns.

The individual stages of analysis required to complete the project and their scoring are presented below:
⃝ Data Processing.
  • As an experienced Data Scientist, you probably know the individual steps
    that need to be performed at this stage, so we will not detail them here.
⃝ EDA, i.e. extensive data exploration.
    Describe the conclusions drawn from each graph, support your hypotheses with statistical tests
    such as t-test or Chi-square. Additionally, answer the following questions:
  • How does a FICO score relate to a borrower's likelihood of repaying a loan?
  • How does credit age relate to the probability of default and
    whether this risk is independent of or related to FICO score?
  • How does home mortgage status relate to the likelihood of default?
  • How is annual income related to the probability of default?
  • How is employment history related to the likelihood of default?
  • How is the size of the loan requested related to the probability of default?
⃝ Feature Engineering – create 20 new variables.
⃝ Modeling.
  • Cluster the data (try several methods, at least 3) and check whether there are any borrower segments,
    use appropriate methods to determine the optimal number of clusters.
  • Train 5 different models, using a different algorithm for each,
    and then compare their performance, using the AUROC score as the model quality metric.
  • Check the operation of previously used methods on compressed data using PCA,
    compare the results (AUROC score) with the models trained in the previous section.
  • Build the final model whose AUROC score will be >= 80%, remember to select important variables,
    cross-validate and tune model parameters, also think about balancing classes.
