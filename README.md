# WebServer
Weather web application that takes in a location or a zip code and returns
the locations weather forecast and temperature. The main focus of this project was the 
backend, which was created using express(NodeJS module). The handlebars module was used to 
create views and partials. The views are the weather, about, help and the 404 screens which are dynamically
populated with data from a JSON object and partials which were used to load the same header and footer 
for all screens. The path module was used internally, so that it would be easier to tell the
handlebars module and express module, where to look for what pages to load. The request module was used 
to handle the HTTP request, this is how I interacted with the API's.

Two API's(application programming interface) were used for the weather application, the Mapbox geocoding API which
takes in an address and returns the latitude, longitude and location and the weather stack API which takes in
the latitude and longitude and returns the weather description and temperature of the location.

The weather screen:
![image](https://user-images.githubusercontent.com/102123401/162993642-72112629-a564-4af8-ac60-d03de38ed6a8.png)

The about screen:
![image](https://user-images.githubusercontent.com/102123401/162993857-2107b836-093a-48db-a33f-0bfa9c07c86f.png)

The help screen:
![image](https://user-images.githubusercontent.com/102123401/163011614-b8fdebd4-6573-4b15-8f5b-3500635ef258.png)

The 404 screen:
![image](https://user-images.githubusercontent.com/102123401/163012479-dc56f50d-142e-4075-a916-20cec59c52bc.png)

