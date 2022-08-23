# String Review

## Due: DoW MM/DD at 11:59 PM

- Create a program called `StringReview.java`
- Prompt the user for a phrase
- Find the index of the first occurence each of the following characters in the phrase: t, i, g, e, and r
- If t and g are in the String, return the substring from t to g (including g)
- If g is not in the String, return the substring from t to r (including r)
- If t is not in the String, return the substring from g to r (including r)
- If neither t nor g are in the String, return the substring from e to r (including r)

***Example Input:***\
today is great day\
***Example Output:***\
today is g

***Example Input:***\
today i went for a run\
***Example Output:***\
today i went for a r

***Example Input:***\
i saw a gorilla\
***Example Output:***\
gor
