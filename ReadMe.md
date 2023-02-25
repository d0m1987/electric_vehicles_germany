# (Electric) Vehicle registration in Germany over time

## Motivation & goals
The Kraftfahrtbundesamt releases a monthly .xlsx with the amount of newly registered cars.  
This data is freely available under this [link](https://www.kba.de/DE/Statistik/Produktkatalog/produkte/Fahrzeuge/fz10/fz10_gentab.html).  

I'm very interested in knowing, how the registrations of newly registered (electric) cars has developed over time.  
Sadly, the data is split in monthly released .xlsx sheets and the format has changed a bit over time.  

So the goals of this repository are:  
1. Provide the data in a format, such that other people can work more easily with it. You will find...  
1.1. ... an easily consumable .csv with the data  
1.2. ... an easy to spin up REST webservice with the data
2. Visualize the data in a dashboard, such that you can have a first glimpse at the data without need to build something on your own