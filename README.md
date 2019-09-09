<h2>Database schema optimization</h2>

Created an efficient database schema to store raw bus data into postgres/postgis to allow efficient queries. The new database uses foreign key indexes to improve performance and eliminates repeating groups to make it easier to investigate data with SQL queries. Bus stops were compared with passing routes to find routes with the most stops and stops with the most passing routes. Each route was analyzed to find which route had the highest amount of cumulative boardings, alightings, and stops, which may make it an ideal candidate to provide an express bus on the same route.
Interactive Maps indicating the busiest bus stops and longest bus routes were created. 
<br>
Links: 
<ul>
<li><a href="https://github.com/harrydurbin/chicago-bus-analysis/blob/master/chicago_bus.ipynb">iPython Notebook code</a></li>
<li><a href="https://chicago-bus.herokuapp.com/map-routes">Interactive map of longest bus routes</a></li>
<li><a href="https://chicago-bus.herokuapp.com/map-stops">Interactive map of busiest bus stops</a></li>
</ul>
<br>
Figure 1: Database schema design
<img src="../master/img/db_schema.jpg?raw=true" width="100%"/>
<br>
Figure 2: Screenshot of Busiest Bus Stops Map (number of routes associated with each stop)
<img src="../master/img/bus_stop_map.jpg?raw=true" width="100%"/><br>
<br>


