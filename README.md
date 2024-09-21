# Portugese-Bank-Marketing-
Data Science, ML Project
# Problem Statement

Task 1:-Prepare a complete data analysis report on the given data.
Task 2:-Create a predictive model which will help the bank marketing team to know
which customer will buy the product.
Task3:-Suggestions to the Bank market team to make customers buy the product.

### Dataset Link:
This dataset is about the direct phone call marketing campaigns, which aim to promote
term deposits among existing customers, by a Portuguese banking institution from May
2008 to November 2010.
# Domain: Finance/Banking

## Attribute Information:
## Input variables:
1 - age (numeric)
2 - job : type of job (categorical: &#39;admin.&#39;,&#39;blue-
collar&#39;,&#39;entrepreneur&#39;,&#39;housemaid&#39;,&#39;management&#39;,&#39;retired&#39;,&#39;self-
employed&#39;,&#39;services&#39;,&#39;student&#39;,&#39;technician&#39;,&#39;unemployed&#39;,&#39;unknown&#39;)
3 - marital : marital status (categorical: &#39;divorced&#39;,&#39;married&#39;,&#39;single&#39;,&#39;unknown&#39;; note:
&#39;divorced&#39; means divorced or widowed)

4 - education (categorical:
&#39;basic.4y&#39;,&#39;basic.6y&#39;,&#39;basic.9y&#39;,&#39;high.school&#39;,&#39;illiterate&#39;,&#39;professional.course&#39;,&#39;university.degr
ee&#39;,&#39;unknown&#39;)
5 - default: has credit in default? (categorical: &#39;no&#39;,&#39;yes&#39;,&#39;unknown&#39;)
6 - housing: has housing loan? (categorical: &#39;no&#39;,&#39;yes&#39;,&#39;unknown&#39;)
7 - loan: has personal loan? (categorical: &#39;no&#39;,&#39;yes&#39;,&#39;unknown&#39;)
  related with the last contact of the current campaign:
8 - contact: contact communication type (categorical: &#39;cellular&#39;,&#39;telephone&#39;)
9 - month: last contact month of year (categorical: &#39;jan&#39;, &#39;feb&#39;, &#39;mar&#39;, ..., &#39;nov&#39;, &#39;dec&#39;)
10 - day_of_week: last contact day of the week (categorical: &#39;mon&#39;,&#39;tue&#39;,&#39;wed&#39;,&#39;thu&#39;,&#39;fri&#39;)
11 - duration: last contact duration, in seconds (numeric). Important note: this attribute
highly affects the output target (e.g., if duration=0 then y=&#39;no&#39;). Yet, the duration is not
known before a call is performed. Also, after the end of the call y is obviously known.
Thus, this input should only be included for benchmark purposes and should be
discarded if the intention is to have a realistic predictive model.
other attributes:
12 - campaign: number of contacts performed during this campaign and for this client
(numeric, includes last contact)
13 - pdays: number of days that passed by after the client was last contacted from a
previous campaign (numeric; 999 means client was not previously contacted)
14 - previous: number of contacts performed before this campaign and for this client
(numeric)
15 - poutcome: outcome of the previous marketing campaign (categorical:
&#39;failure&#39;,&#39;nonexistent&#39;,&#39;success&#39;)
social and economic context attributes
16 - emp.var.rate: employment variation rate - quarterly indicator (numeric)
17 - cons.price.idx: consumer price index - monthly indicator (numeric)
18 - cons.conf.idx: consumer confidence index - monthly indicator (numeric)
19 - euribor3m: euribor 3 month rate - daily indicator (numeric)

20 - nr.employed: number of employees - quarterly indicator (numeric)
Output variable (desired target):
21 - y - has the client subscribed a term deposit? (binary: &#39;yes&#39;,&#39;no&#39;)

# Model Comparison Report
Create a report stating the performance of multiple models on this data and
suggest the best model for production.
# Report on Challenges faced
Create a report which should include challenges you faced on data and
what technique used with proper reason.
