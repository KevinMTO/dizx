# dizx
A qudit version of PyZX

DiZX ports some of the functionality of PyZX to work for qudits (specifically qudits of odd prime dimension). It currently only works with stabiliser (i.e. Clifford) diagrams.

DiZX can convert circuits into ZX-diagrams, visualise these diagrams, automatically simplify them to graph-like form and to the affine with phases normal form.
If you want to play around with DiZX, it is best if you start with trying the functionality in the notebooks folder.

Note that DiZX is still firmly in Alpha. You might encounter many bugs. In particular, the ability to generate a tensor representation of a diagram is not yet implemented, 
meaning that some of the rewrites might inadvertently be breaking the semantics.
