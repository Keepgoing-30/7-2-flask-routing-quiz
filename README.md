[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/4MRoawZk)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=22006963)
# This Codespace is to help you answer the quiz questions in Canvas Quiz 7.3

### You don't need to commit or synchronize the code from this Codespace
This week's module, the last in the course, includes a Final Project that replaces a traditional Final Exam. This Final Project combines all of the Career Connections you have completed to date as well as new concepts introduced this week. This quiz is designed to ensure that you have learned what you need to learn to be able to complete the Final Project.

There is a program called `fertilizer_catalog.py` in the Codespace so you can use it for this quiz. The quiz will ask you about aspects of the program.

## Submit the answers to these questions in Canvas Quiz 7.3

1. Running the fertilizer_catalog.py creates a Flask app that launches a browser. Placing the URL `http://domain/type?ftype=Nitrogen` will result in what? (domain in the URL above is a placeholder for a temporary domain name CodeSpaces provides)

2. Running the fertilizer_catalog.py creates a Flask app that launches a browser. Placing the URL `http://domain/cost?price=50` will result in what? (domain in the URL above is a placeholder for a temporary domain name CodeSpaces provides)

3. In the Python code expression  `cursor.execute("SELECT * FROM fertilizers WHERE brand = ?", (the_brand,))` why is there a comma after the variable `the_brand`, as in `(the_brand,)`?

4. What happens if you enter into a running fertilizer_catalog app a URL requesting a particular fertilizer brand, but forget to include the brand name?
(For example: `http://domain/brand?name=` should have been `http://domain/brand?name=BloomBoost Pro`)

5. According to the program, what happens if you ask for a brand of that is not in the database?

6. The previous question asked about the consequence of asking for a brand that is not found in the database. How does the program determine that the brand is not found in the database?

7. Once I submit a URL of the form `http://domain/brand?name=BloomBoost Pro` the browser converts it to
`http://domain/brand?name=BloomBoost%20Pro`. Why?

8. What is the primary cursor method used to pull rows from the results of an SQL query in the `fertilizer_catalog.py` program?

9. What does the `jsonify` function do?


10. What is the name of the database and table in the `fertilizer_catalog.py` program?
