# Loan-Eligibility-Predection
**Loan eligibility** is defined as a set of criteria basis which a financial institution evaluates to decide the eligibility of a customer for a particular loan.
**Loan eligibility** is decided after a long and intensive process of verification of documents and validation of set of criteria like loan amount, Marital status, Applicant income ,Credit history etc... which takes up a huge amount of time.
This time consuming process can be avoided by developing a system that can predict whether a person can be eligible for a loan based on the information filled in the loan application form which has all the criteria for validating eligiblity.
**Supervised Learning** is used in this project. In Supervised Learning machine is trained using labeled data. The algorithm learns from labeled training data and predicts outcomes for unseen data.

**Supervised Learning** consists of two algorithms :
1. **Classification** : Decision Tree, Random Forest, Naive Bayes.
2. **Regression** : Simple Linear Regression, Polynomial Regression, Multiple Linear Regression.

In Classification basically a class is predicted for given example of input by learning through labels of training data. It is used when a categorically prediction needs to be made. Algorithms like Decision Tree, Random Forest, Naive Bayes are supervised classification algorithm while regression is a statistical method to model relationship between dependent or the target and the independent variable and predict the values of dependent variable.
It is usually used when the outcome we wish to predict is continuos.
Since we need to determine whether a person is eligible for loan hence we will be using classification algorithm. We will be using two algorithms and choose the ones which provides the best accuracy.
**Decision Tree Algorithm** is used for both classification and regression however it is mainly used for classification.

**How does Decision Tree develops a classification model ?**
It forms a tree like structure. It consists of non terminal nodes, root nodes along with internal nodes. The branches represents the outcome of the rule either yes or no. The internal nodes represents the attribute of the dataset and leaf node is the final class or the decision made.
Here the algorithm asks a question in the form of condition or rule and decides the answer as yes or no.
**Naive Bayes** is also used in this project. **Naive Bayes** is a simple yet fast and accurate, and reliable classification algorithm. It works on probability of occurrence and uses Bayes theorem for calculating the probability.

**Python** is used in this project as it is simple and code is readable. It provides various libraries which play a crucial role in machine learning, data science, data visualization, data analytics, etc.
Libraries Used in the Project :
1. **Pandas**        : For Data Analysis, manipulation and filtering.
2. **Numpy**         : For performing mathematical and logical operations on arrays.
3. **matplotlib**    : For creating static, interactive and animated visualizations.
4. **scikit-learn**  : Most useful library with efficient tools for machine learning and statistical modeling including range of supervised and unsupervised learning algorithms.
