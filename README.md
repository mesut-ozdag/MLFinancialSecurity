# MLFinancialSecurity
## Predicting the vulnerability category of a smart contract from extracted source-code features
For this project, SmartBugs-Curated is used, which is public on GitHub. It was created as a curated dataset of Solidity smart contracts annotated with tagged vulnerabilities, and SmartBugs’ own dataset documentation lists it as 143 curated vulnerable contracts. A related description also notes 10 DASP-derived vulnerability categories, which makes it a good fit for a multi-class supervised learning lecture rather than a simple safe-vs-vulnerable binary task.

https://github.com/smartbugs/smartbugs-curated

SmartBugs-Curated:

• multi-class classification of vulnerability type

• feature extraction from Solidity code

• Logistic Regression vs XGBoost comparison
