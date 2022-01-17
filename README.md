# Notes
This is a reproduction project of the master thesis "Applying API Categories to the Abstractions Using APIs" (2021) written by Katharina Gorjatschev as part of the MSR course 2021/22 at UniKo, CS department, SoftLang Team.

# Team Name: Whiskey
* Gayatri Tawada (219203030)
* Shivam Rajendra Nirhali (219203376) 

# Baseline Study: 

### Aspect of the reproduction project
In the “Collection and Selection of Repositories” part of the thesis, they have mentioned that they would use “100 stars, 100 commits and two contributors” to filter out the obscure projects from the GitHub API. We would like to change these conditions by either increasing or decreasing the values and we would like to analyze the dependencies on the changed conditions.

### Input data:
Collecting the dependencies from github repositories using github APIs with filteration values 150 stars 150 commits and 2 contributors.  

### Output data:
CSV files containing dependencies of repositories inside output folder.
 
# Finding of Replication:
 
### Process delta: 
We changed the filter criteria values to 150 stars 150 commits and 2 contributors.

###  Output delta: 
Repositories collected was 4250  and total dependencies observed were 45973.

# Implementation of Replication: 

### Software
* Java 11 (Maven project)
* Python 3.9( pyspark==3.1.2)

### Data
We were able to produce csv files which contain Java repositories name and eligible dependencies file.

# Notes
You need to create a personal access token in your GitHub account and then replace the `USERNAME_AND_TOKEN` in `RepositoriesPicker.java` with your username and token.

# Issues
The maven project required lots of time (5-6 days) to execute code due to limitation of hardware as well as network speed.