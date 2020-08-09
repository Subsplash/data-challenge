# data-challenge
This data analytics challenge provides a form of a coding assessment which allows interviewers and a candidate to be on a common footing during subsequent interviews, more effectively discuss the approaches, thought processes, and techniques demonstrated in the resulting script.

## Resources
This challenge is based on analyzing election results.
In it's initial form, the solution is intended to be written in Python, but other suitable languages will be considered.
The first resource is a CSV file containing hypothetical election data.

## Challenge 1 -- summarize the election results
1. Import CSV Data

2. Total # of Votes Cast

3. List the counted Counties

4. List the Candidates

5. Tally Votes By County

6. Tally Votes for each Candidate and Declare A Winner

7. Print Results To Stdout and to a text file

## Challenge 2 -- Update the results to a database
1. DDL : Create schema and table(s)

2. DML : Store the results (from Challenge 1)

3. Report : Query and display the stored data, to verify that it's accurate

# References

## Example Results
```text
Election Results
------------------------------------------
Total Votes: n,nnn,nnn
------------------------------------------
Votes by county:
County1: n.nn% (nnn,nnn)
County2: n.nn% (nnn,nnn)
County3: n.nn% (nnn,nnn)
------------------------------------------
Votes by candidate:
Candidate1: n.nn% (nnn,nnn)
Candidate2: n.nn% (nnn,nnn)
Candidate3: n.nn% (nnn,nnn)
------------------------------------------
Winner: Candidate?
------------------------------------------
```