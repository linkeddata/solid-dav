# solid-caldav
Allow solid clients to think of caldav as linked data, and maybe even sync

Given that we have a log of solid support libraries and 
a various dav (caldav, carddav, webdav) clinet libraries,
should it not be easy to 

- allow a linked data styem to look at a dav space as thogh it were lnked data
- sync between a solid store and a dav store with the same data
- develop calendar, contacts etc servers which operate as part  of the leacy silod dav space but also the new interconnected 
The DAV protocols in a way encapsulate the problem solid came to solve:
you have to design a new protocol and build a new server for each application,
wheras with solid you have to design the footprint of each objects in the read-wrote-web, 
but you don't have to design or buld anything new on the backend.

Not sure I will have to actually write this, so very interested in any takers out there in the interwebs.

timbl
2016-12-03
