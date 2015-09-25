## Development of APIs for environmental investigations

Earth scientists are increasingly required to think across disciplines and utilize a wide range of datasets in order to solve complex environmental challenges. Although significant progress has been made in distributing data, researchers must still invest heavily in developing computational tools to accommodate their specific domain. They must also adhere to a wide array of different metadata and formatting protocols in order to meet federally-mandated data sharing guidelines. 

This project aims to develop lightweight computational data systems aimed at enabling rapid data distribution, analytics and problem solving tools for Earth science applications. We are building Application Programming Interface (API) systems that are easily deployed in the cloud, and that provide access to databases and model output through a REST web architecture. These tools are built to be scalable and adaptable to changing agency metadata requirements, enabling the researcher to focus on science rather than data reformatting. 

![API Graphic](/apiGraphic.JPG)

This graphic illustrates the framework of our 'ice2ocean' API. We run our backend components on a Microsoft Azure Linux virtual machine, which hosts our PostgreSQL relational database and output from an energy balance snow runoff model. Clients can make calls through the API to access our field and airborne observations, associated metadata, as well as gridded maps of model output such as precipitation and runoff. These data can be served to any number of web clients.

## Project participants:

*[Rob Fatland] (http://www.robfatland.net/)
*[Anthony Arendt] (http://psc.apl.uw.edu/people/investigators/anthony-arendt/)
*[Bill Howe] (http://escience.washington.edu/content/bill-howe-cse)
