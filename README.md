Fly Away With Me
----------------

Input
----

* people:
	* per path edge

* locations:
	* list of nodes

* times:
	* arrival OR departure time per node, OR
	* total time from start to end

* price:
	

Output
----

* cost
* node list of nearby layovers
* duration within each ...
* import / export query

Features
----
1. hidden city ticketing
	ie to fly from LAX-ORD -- it's sometimes cheaper to buy an LAX-ORD-MKE ticket and just get off at ORD and not take the connection
2. shipping your luggage
3. angular js is frontend, django backend

> Say I want to visit Scotland next month
> I don't care for how long as it's longer than seven days
> I don't care where I land
> > for example:
> > X needs to fly to Chicago to meet up with me before we leave
> > So search:
> > > "INIT all flights that gets one person to Chicago"
> > > "THEN all flights two people to Scotland"
> > > RET [ layovers ]
> > > PROMPT if interesting in [ layovers ]
> > > SPLIT trip if layover, add Y days for vacation time
> > > identify the cheapers intervals
> > > RET trip proposals

* [sabre REST](https://developer.sabre.com/docs/read/REST_APIs)
