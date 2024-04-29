DataGrokr Assignment 2 <br>
Question was: Write a Good README file/doc <br>
Project Description: <br>
  Suppose there is a repository called ‘country-capital-api’ that houses the code
  for an API written in Python and Flask that returns the name of the country if a 
  capital city is provided. The ASGI server Uvicorn is used to serve
  this API. Also, there is a microservice endpoint for this API available at
  https://example.com/country-capital/<query-params> that can be used
  by any project in the organization to consume this API.



<h1>README file</h1>

# Project Title
The country-capital-api is a Python and Flask-based API that provides functionality to retrieve 
the name of a country based on a provided capital city. The API is served using the ASGI server 
Uvicorn. Additionally, it offers a microservice endpoint available at 
https://example.com/country-capital/<query-params> 
which allows integration within various projects across the organization, enabling them to query country names through capital city parameters.


## Development 
    1. Clone the Repository:
    Command: git clone https://github.com/yourorganization/country-capital-api.git

    2. Install Python
    Ensure Python 3.x is installed on your system. You can download it from https://www.python.org/downloads/

    3. Install Dependencies:
    Command : pip install -r requirements.txt

    4. Run the Application:
    Command: uvicorn main:app --reload



## Prerequisites
    1. Python
    2. Flask
    3. Uvicorn
    4. Git
    5. Internet access
    6. API Testing tool




