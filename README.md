# Swift-Route-Logistics-Dashboard

Swift Route Logistics - My First Big Power BI Project
Hey Thanks for stopping by. This is a project I've been working on to solve some real world headaches in the logistics business i  call it Swift Route  basically  wanted to see if i could use data to figure out why deliveries get delayed and how to keep the trucks running longer without breaking down.

The Problem
The company was having trouble keeping track of different moving parts they had issues with hubs getting too crowded and vehicles breaking down unexpectedly  i used this data to see if we could predict these problems before they happen.

Key Parts of the Project
Hub Capacity: I compared how many orders each hub handles against its actual limit in the dashboard you can see that certain hubs are consistently overloaded which causes most of the shipping delays.
([ub overview dashboard.png](https://github.com/bassibruh/Swift-Route-Logistics-Dashboard/blob/3c8737df406b6a0799cd9c022fcac2ad525ba3fb/hub%20overview%20dashboard.png))

Driver Performance: I looked at whether more years on the job actually results in better customer ratings the data shows some interesting gaps where experience doesn't always match up with on-time delivery.
(https://github.com/bassibruh/Swift-Route-Logistics-Dashboard/blob/3c8737df406b6a0799cd9c022fcac2ad525ba3fb/driver%20overview%20dashboard%20.png)

Vehicle Maintenance: I tracked the age of the trucks against their breakdown frequency this helps in deciding when to retire a vehicle instead of spending more money on repairs.
(https://github.com/bassibruh/Swift-Route-Logistics-Dashboard/blob/3c8737df406b6a0799cd9c022fcac2ad525ba3fb/vehicle%20overview%20dashboard.png )    



How I made it
I used Power BI for the whole process first I cleaned up the raw data in Power Query because it had a lot of inconsistencies then I used DAX to create measures for things like delivery rates and hub stress levels the final report is meant to be a simple tool for a manager to check daily.

Insights found
Some hubs are hitting 100% capacity during peak hours while others stay half empty rebalancing the load could fix a lot of the delay issues.

There is a clear "breaking point" age for the vehicles once a truck hits a certain age the maintenance costs jump up by a lot.

On-time delivery is lowest during specific shifts suggesting we might need better staffing at those times.


A couple of things i will  fix next time
I'm still learning  so there are a few things i will do better next time i want to add more Predictive stuff like actually forecasting how many orders will come in next month so the Hubs can prepare better. Also, I think the "Morning Shift" data needs a deeper look because that's where most of our delays are happening



