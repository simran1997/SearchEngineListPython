I take a query string as an input from the user. Then it pull out the sentences matching this query that has been input by the user in decreasing order of relevance after converting every word in the query and the sentence to lowercase. 

Most relevant sentence is the one with the maximum number of matching words with the query.

Sentences = [“Python is cool”, “python is good”, “python is not python snake”]

Input:
Please input your query string

“Python is”

Output:
3 results found:

python is not python snake
python is good
Python is cool
