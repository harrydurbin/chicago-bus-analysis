# chicago-bus-analysis

Created an efficient database schema to store raw chicago bus data into postgres/postgis to allow efficient queries. The new database uses foreign key indexes to improve performance and eliminates repeating groups to make it easier to investigate data with SQL queries. Bus stops were compared with passing routes to find routes that have the most stops and stops that have the most passing routes.
Interactive Maps indicating the busiest bus stops and longest bus routes were created at the following heroku links: <br/>
https://chicago-bus-routes.herokuapp.com/chi-bus-maps.html <br/>

![alttag](https://github.com/harrydurbin/chicago-bus-analysis/blob/master/img/db_schema.jpg)

