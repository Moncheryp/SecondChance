# SecondChance
This program uses a database to suggest career options for individuals over 18 with a history of justice involvement. It aims to help them explore and pursue meaningful careers despite their past interactions with the justice system.

Aspects of my code:

1. `ask_yes_no_question` 
    - This function takes a question as input and prompts the user to answer with "yes" or "no."
    - It continues to prompt the user until a valid response is received.
    - The function returns `True` for a "yes" response and `False` for a "no" response.

2. `suggest_career_options` 
    - This function provides career suggestions based on the user's age and legal history.
    - It first checks the user's age and informs them if they are not eligible for the program (age less than 18).
    - It then asks whether the user has a felony or misdemeanor history.
    - For users with a felony history, it suggests specific careers and checks for disqualifying felony charges.
    - For users with a misdemeanor history, it suggests specific careers.
    - The function also provides additional areas for consideration based on the user's profile.
    - A list of organizations for employment services is included in the suggestions.

3. `main` 
    - The `main` function acts as the entry point of the program.
    - It runs a loop where it calls the `suggest_career_options` function and prints the career suggestions.
    - After each iteration, it asks the user if they want to continue. If the user chooses to stop, the loop breaks, and the program ends.

4. Organizations for Employment Services:
    - The list of organizations for employment services is stored in the `employment_organizations` variable.
    - This list is displayed at the end of the career suggestions, providing users with resources for further assistance in finding employment.

5. Execution:
    - The program starts by welcoming the user to the Second Chance program.
    - It then collects information about the user's age and legal history.
    - Based on this information, it suggests careers and additional considerations.
    - Finally, it provides a list of organizations for employment services.
