## Skyscanner Clone

The project is a web clone based on [SkyScanner page](https://www.skyscanner.com/)

### Main Function 
Given departure, destination and range of acceptable departure date.

The project is focus on the use of an API in order to connect the flights information to the frontend of application looking for create the similar appereance, respect to the original web site.

![image](https://i.ibb.co/C57Br4J/Original-Skyscanner.png)


![image](https://i.ibb.co/KywLQ38/Skyscanner-Our.png)

The appereance is very similar, but we use the advantages of react. For instance, in the original website, the navigation between __Flights__, __Hotels__, __Car hire__. We create components for each one, and the DOM do not have to recharge all the page.

We also create a component for the Information Page. In order to make understable the code for anyone to wants to use for improving the solution.


Here is compared between original and the current project.

Covid Map Banner
![Original Map](https://github.com/BrianFs04/skyscanner_clone/blob/master/src/originalMapBanner.png)
With the clone
![Copy Image](https://i.ibb.co/NFt7FPK/covid-Banner-Our.png)


Information Banner
![Orginal banner](https://github.com/BrianFs04/skyscanner_clone/blob/master/src/originalBanner.png)
with the clone
![no original banner](https://github.com/BrianFs04/skyscanner_clone/blob/master/src/copybanner.png)


And so on..

The use of css, react components here, render the info page in a fast way, compared with the original that is directly writing on the index.


We have the functionality based on the use of a Flights information API. We use the free Skyscanner Rapid API

![image](https://i.ibb.co/vZqxFpG/Rapid-API1.png)


This API is useful for the scope of the project, that just is showing the functionality for the user of selecting the flights between to places, in certain date. The esential value of skyScanner. 

This API is based on the original Skyscanner API, and the documentation of this API worked in order to understand the funtionality and key in the free API

![image](https://i.ibb.co/qYwBkdX/Original-Sky-Scanner-API.png)

So the functionality, in general terms. can be described by the next architecture

![image](https://i.ibb.co/Rvjtgc9/Architecture-Skyscanner-drawio.png)

This is used a lot in the flights component

![image](https://github.com/BrianFs04/skyscanner_clone/blob/master/src/flightcomponent.png)

Where yo can write the origin and destination places

![image](https://i.ibb.co/p3Rkv7t/Flights-Places.png)

Choose the date, since the current day. Avoiding misuse of the flights search bar.

![image](https://i.ibb.co/0rtZmm9/Flight-Calendar.png)

The results is presented in another route, with a component

![image](https://i.ibb.co/L1X33Nh/Flights-Results.png)



## Technologies used

- React
- React DOM router
- Material UI
- Bootstrap
- Javascript
- CSS
- HTML

### Tools
Rapid API SkyScanner free API endpoints
![image](https://i.ibb.co/m9hf7WC/Rapid-API2.png)

## Authors
[Brian Florez](https://brianfs04.github.io/mywebpage/)

[Pilar Pinto](https://pilarpinto.github.io/)
