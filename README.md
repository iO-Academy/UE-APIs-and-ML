### University of Edinburgh 
# APIs and Machine Learning

### Pre-course material
Before this course starts, please follow the guide linked below:  
[Pre-course guide](./prep-course.md)

### Introduction to APIs
- [What is an API](https://www.freecodecamp.org/news/what-is-an-api-in-english-please-b880a3214a82/)?
  - What do we use them for? Why?
  <img src="./rest-api.png" width="450" />
- HTTP(s)
  - Requests/Responses
- HTTP Requests from Python
  - [Requests](https://pypi.org/project/requests/) lib
  - EXERCISE 1 - Interacting with an API
    ```
    Get the latest Bitcoin price data and output the price of one bitcoin in USD
    ```
- API Structures
  - [REST](https://restful-api.dev/rest-fundamentals/#rest)
    - [HTTP Verbs](https://restful-api.dev/rest-fundamentals/#get)
    - [HTTP Status Codes](https://www.restapitutorial.com/httpstatuscodes.html)
    - URL Structures (Resources)
    - EXERCISE 2 - GETting data
    ```
    Output the name and crew size of star starship with ID 3 from the Starwars API
    ```
    - EXERCISE 3 - Updating data
    ```
    Send a PUT request to post ID 1 to change the title and/or body
    ```
  - GraphQL
    - Problems with REST
    - [Demo](https://countries.trevorblades.com/)

- [ChatGPT API](https://platform.openai.com/docs/quickstart?context=python)
  - [API keys](https://platform.openai.com/api-keys)
  - [OpenAi pip library](https://pypi.org/project/openai/)
    - `pip install --upgrade openai`
  - EXERCISE 4 - Recreate a lecturer
    ```
    Simulate a lecturer for a Masters in Finance, Technology and Policy having a conversation with you, a student
    ```

- [Pandas](https://pandas.pydata.org/)
  - What is it?
  - Dataframes
  - EXERCISE 5
  ```
  Load credit card fraud data from our API and put it into a Pandas Dataframe
  ```
