# watching-traffic-go-by

Are your traffic counts in weird formats?  Don't know what to do with them?  Outside of Traffix and Synchro, we aren't sure either.

Thus we are exploring data standards and formats to visualize and make our traffic counts more useful.

We also want to inventory all our old traffic count data (and eventually pedestrian and bike counts) to this same format.

## Plan
We think the end result will be:
Traffix XML -> Pandas/CSV -> Shared Streets -> Remix
Traffix XML -> Pandas/CSV -> Modeling format for use with CUBE

## Research
[TransXML](http://www.aashtoware.org/Documents/TransXML%20Resolution.pdf) - Looks like a dead format

[UTDF Paper](http://www.ctre.iastate.edu/pubs/midcon/Gerken.pdf) - Very little documentation

[UTDF Trafficware](http://www.trafficware.com/transferring-data-using-utdf.html) - Much of the work around this seems program specific

[Traffix Notes from Shanti](https://github.com/vta/watching-traffic-go-by/blob/master/import_traffix_values.pdf) - We pulled certain data from the Traffix file based on suggestions from one of our traffic engineers.
