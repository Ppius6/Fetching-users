# Introduction

This README file provides a brief explanation of a Python code that fetches user data from an API using the requests and json libraries.

# Code Overview

The code begins by setting the URL endpoint and parameters for the API request. In this case, the URL is set to https://randomuser.me/api, and the parameters are set to request 100 results and filter by male gender.

Next, the code makes the API request using the requests.get() method, passing in the URL and parameters as arguments.

The response from the API is then parsed using the json.loads() method, which converts the JSON-formatted response data into a Python dictionary.

The user information is then extracted from the dictionary and stored in a users variable.

Finally, a loop is used to iterate through the users and print their information, including name, email, and phone number.

This Python code provides a simple example of how to fetch data from an API and parse the response using the requests and json libraries. The code can be easily modified to request different data from the API and process it in various ways, making it a useful tool for working with APIs in Python.
