# Sample Star Wars API Documentation

## Getting Started with SWAPI

In this module we are walking the reader through how to use the Star Wars Open API (https://swapi.co) to search for a movie that features Luke Skywalker.

## SWAPI Basics

The SWAPI is a database with all different kinds of resources from the Star Wars universe.
There are 6 main resources we can tap into:

- People: 87
- Films: 7
- Starships: 37
- Vehicles: 39
- Species: 37
- Planets: 61

Each of these resources has various attributes we can access as well as different ways we can access them. The `SWAPI` is completely open API so there is no need for an API key, however, it is limited to 10,000 API requests per day, per IP.

To make a request all we need is the base URL:
`http://swapi.co/api/`

From there we can choose which resource we want to tap into.

## Getting Info From The Call

If we make a simple call to the SWAPI we can use the JSON response to get information from that call. We can also specify a format (API/JSON/WOOKIEE) for the GET request. 
Lets use the `Films` resource as an example since that's what we'll be working with.
If we make a simple call to:
`https://swapi.co/api/films/?format=api` , we will see something like this :
