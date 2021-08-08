# BasicAuthentication

Implementing basic authentication in Web API using .NET 5

The example API has one endpoint/route to demonstrate authenticating with basic http authentication and accessing a restricted route:

/WeatherForecast - secure route that accepts HTTP GET requests and returns weather forecast for five consecutive days if the HTTP Authorization header contains valid basic authentication credentials. If there are no basic auth credentials or the credentials are invalid then a 401 Unauthorized response is returned.
