# AnimalBehaviorDataBase
A database collection of farm animal behaviour phenotypes for modelling exploration.

# Goal
Complete solution of the animal monitoring behavior problem.

To provide a source of animal behaviour data that can be exploited for development of mathematical models.  

To promote data sharing and collaborative projects for characterizing animal behaviour. 

## Methods
- Development generic machine learning models based on different data sets.

- Concentration of efforts for solving of specific problems by collaboration.

- Comment Rafael: I thought initially to focus only in the sharing of data. But if I interpreted well, Victor proposed to include also code of maching learning methods? 

Comment: For the sections below, I think it will be important to include the name of the owner of the data, his/her affiliation, email 

## Valorization 

- we need to propose a way to valorize this work. We can be content of having the GitHub repository or to go further and write a common data paper. For the data paper, I think we should check that the data has not been presented in other data paper. If this is the case, we will need to cite the data papers already published. I think that we can explicitely propose as outcome the data paper where all collaborators will be included as authors. We can say that we want to promote open science via free dissemination models such ash Peer Community In Animal Science (https://animsci.peercommunityin.org/)


# Cows
## Cow behavior
| link | Size | Variables | Model | Paper |
|------|------|:---------:|-------|-------|
| https://zenodo.org/record/3981400 | 40Gb | Frames | Deep learning | in review |
| https://www.mdpi.com/1424-8220/20/17/4741/xml | 89Mb | X, Y, Z, Ax, Ay, Az | Linear mixed model | https://www.mdpi.com/1424-8220/20/17/4741/xml |
## Cow indoor localization
| link | Size | Variables | Model | Paper |
|------|------|:---------:|-------|-------|
| https://zenodo.org/deposit/3900340 | 50Gb | RSS x 10 stations | Trilateration | https://www.mdpi.com/1424-8220/20/14/3841 |
## Cow outdoor localization

# Pigs
## Pigs behavior

# Suggestions for the data formats
## Tag acceleration
Files in .csv format with ';' as the delimiter.

Example

| CowNo | DateTime | Ax | Ay | Az | Reference behavior |
|-------|----------|----|----|----|--------------------|
| 1234 | 2020-01-01 11-25-30 | 500 | 600 | -700 | Standing |
