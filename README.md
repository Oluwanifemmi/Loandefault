# Loandefault

This code is a solution to the below problem:
I run a small fund that does programmatic loan investing using a service called Prosper. 
Prosper offers what are called "P2P" fractional loans. The basic idea is as follows: 
- End users apply for loans on the Prosper website - Investors get a semi-anonymized view of each loan -
- Based on the parameters of the loan, an investor can invest as little as $25 per loan or as much as the whole loan.
Slots are reserved on a first-come, first-serve basis. - Investments are made via a Prosper-provided API. Currently,
I use a simple set of parameters to choose the loans. This has worked OK so far but it is a very crude approach. Before stepping up the investment amounts,
I would like something a bit more sophisticated. Prosper offers back data for their loans.
I would like a data scientist to model a straightforward system to predict the ROI for an investment,
which would determine the amount I would invest on each loan. I would then like this backtested against my current approach to see what the value-add would be.
