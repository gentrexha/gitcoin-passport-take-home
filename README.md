# Gitcoin Passport Data Science Take-home Problem
2022-07-12

Questions:

- Jeremy Dillingham // Jeremy@gitcoin.co // @jkd_eth (telegram)
- ???

Instructions:

- Please limit your analytics work to 2 hours. You can use any resources or tools you like.
- Prepare for a 30 min presentation and discussion of your work and results.
- You can use up to 30 min after you complete your analysis to prepare your presentation materials. Use the medium you find most most useful such as jupyter notebooks, paper, slides, dance, etc. 

Data:

- Human CSV - Contains Passport data which includes individual credentials obtained for each Eth Address. This is a set of known humans from publicly available data sources.
- Sybil CSV - Contains Passport data which includes individual credentials obtained for each Eth Address. This is a set of known Sybils from publicly available data sources. 
- Data headers: 
publicaddress - Public ETH address of the Passport
Confidence Score - for human
passport - JSON of all Passport data. The key value pair of 'provider': '<credential>' example includes as 'provider': 'POAP' will provide all of the credentials assigned to a Passport.

Task:

- Gitcoin Passport wishes to update the Unique Humanity Score in Gitcoin Passport (passport.gitcoin.co) to better determine if an address should 'pass' and be classified to be human or Sybil. This is the critical feature in the Passport product which is used by partners to protect their communities and products.
- How would you build a model to determine the score? Describe the model you chose, the results, and what you've learned from the data. 
- What Product changes would you recommend based on these learnings?
 - If relevant, describe additional steps you would take and/or methodologies you would explore if given more time. 

Included Files:

- instructions.txt (this file) - human.csv
- sybil.csv