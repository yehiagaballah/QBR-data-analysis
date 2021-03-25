# QBR-data-analysis

QBR stands for *Quartely Business Review*

This code was done to automate outputs for a quartelry review presentation regarding how business improved. I coded this to made it easier for me to generate all the graphs and clean the data I need one time without needing to do this through Excel.

This is a code that uses cases done by the whole global team through SFDC. The cases output is an excel file that is ordered chronologically. Cases have been assigned to all team memebers throughtout 3 regions, EMEA, JAPAC, and Americas

This code can be ran once per quarter after editing the quarter and the user if needed to offer comparsions between

First, We imported, cleaned the unwanted data and selected the data that corresponds to the user we need only and the data that corresponds to the cases this user made.

This data has all the extra columns needed to be apprehended as well. The info line at the end shows the data after being cleaned.

Manual filtering has been used in some cases because there is no list compiling all possible cases (as the case for the country and under which region is it). This can also change from one quarter to the other.


### Next Steps 
1) Generalize this through inputs (making this valid for any user, any quarter and renaming the top users country and user-wise)
2) Take this concept and make it a template used by the whole team across different functionalities across other subteams
3) Maintain this to accomodate any updates done on the SFDC output for cases done
