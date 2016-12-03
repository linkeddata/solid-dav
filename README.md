# solid-dav
Allow solid clients to think of caldav as linked data, and maybe even sync

Given that we have a lot of solid, linked data, support libraries and also
a various \*dav (caldav, carddav, webdav) client libraries,
should it not be easy to 

- allow a linked data system to look at a dav space as thogh it were linked data;
- sync between a solid store and a dav store with the same data; and
- develop calendar and contacts clients which operate as part  of the leacy dav space but also the new interconnected solid space.

The DAV protocols in a way encapsulate the problem solid came to solve:
you have to design a new protocol and build a new server for each application,
wheras with solid, you design the footprint of each objects in the read-write-web, and standardize it between clients,
but you don't have to design or buld anything new on the backend.

Not sure I will have to actually write this, so very interested in any takers out there in the interwebs.

\#help_wanted

timbl
2016-12-03

See eg https://www.npmjs.com/package/dav
