
The idea here is to create a virtual copy of all the source trees
of all the GLUE-AI projects, allowing users to browse and build
all the code from a single checkout tree.

Making this single tree view is possible already, but it will be
bulkier than we might prefer.  Currently we would need to pull
the complete contents of all projects, from their very root.
The reasons why have to do with some of our design decisions
in making the individual projects both flexible and easy to
build, using either maven or other tools of the users choosing.
It is the last point that complicates our efforts to "just make
one build build tree".   
	-- StuB22, 2012-09-18