# meteorologic_station

An arduino that gathers info from envionment and sends it
to a server, then the server parses and stores the data
and provide a nice webpage to see it.

I actually only do the software part of this project.

#Data storage howto

Basically, it goes like this:
    [<UCT Hour>]
    temperature:<temperature>
    pressure:<pressure>
    ... other parameters

Either a new '[' or a EOF char marks the end of
the current data for that Date.

#Good ol' dependencies
I dont have anywhere to keep track of all my dependencies so I
might as well list them here.

node.js:
    mz (MIT)
    mkdirp (MIT)
