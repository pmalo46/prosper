# Prosper Loans Dataset Exploration
## by Patrick Maloney


## Dataset

I selected the Prosper Loans dataset, which contains information on over 110,000 loans, with over 80 variables.  I did some wrangling and decided to look at 10 variables, and filtered around this to about 77,000 loans.


## Summary of Findings

I found that lower loan amounts were the most common to be delinquent, as were loans with the highest estimated return.  The more money people made, the more money they requested to borrow, and thus the more investors they needed to fund their loans.  Most investors stuck to the spirit of peer-to-peer lending and self funded around a third of the loans I looked at.  People were less likely to be delinquent on loans with one or few investors, whereas as the number of investors went up, delinquencies rose as well, at least until the point where Prosper Scores were high enough to qualify for larger investments that required more investors.  I also looked at the role the reason for the loan played in determining how many investors funded a loan and whether or not there was an effect on delinquencies, and in both cases, there was not any convincing evidents that the loans purpose was much of a factor.


## Key Insights for Presentation

In the presentation I wanted to show that smaller loans are the most common on the site, and amounts tend to peak in intervals of 5,000.  I also showed that single investors were by far the most common, and that higher Prosper Scores are generally a good predictor of compliance, while middling scores are the most common for delinquency.  I also focused on how Prosper Score and number of investors together have an effect on compliance. Sure enough, as Prosper Score increases, so does the number of investors, since loan amounts go up.  The riskiest loans appear to be loans with many investors and middling Prosper Scores. 

