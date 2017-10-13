# springboard mini project: json

JSON examples and exercises to familiarize with JSON packages. 
dataset with 500 rows, each with a country and different project name. 

# 1.
group by country names and sort by the count of each country with a project
to find the top 10 countries with the most projects, print the head(10) of the dataframe

# 2.
finding the top 10 major project themes with json_normalize (flat file).
after indexing by 'code', count the number of times a theme appears for a name,
printing the 10 most occurring themes. 

# 3. 
In 2. above you will notice that some entries have only the code and the name is missing. 
Create a dataframe with the missing names filled in. 
load dataframe as flat file with json_normalize. 
there are 11 unique codes and more values accounted for than names (because some names are blank). 
after dropping any missing names and duplicate code/name pairs, there should be 11 rows (one for each code). 
merge the dataframe from 2. with the unique 11 rows to result in a new dataframe with missing values filled in.
