# starwars
A JSON dictionary definition for use with the Qlik Sense Generic REST Connector

When setting fields to integers in the schema, it would cause the load script to break in Qlik Sense.  You may neey to go to each field you wish to use as an integer and update the load script using this syntax:
```
Num#(cost_in_credits,'0.0') AS starship_cost
```
