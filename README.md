this project was to implemented a extended multi-feature SQL which can improve the performence of self join more than 300% when the data size gets large.

As we know, there are lots of internal results generated when involes self join which is crazy slow. One way to solve this problem was to extend the standard SQL and define a new "such that" clause which take care of different groups of the table that satisfy certain constraints. By doing this, we can avoid doing many self joins and can imporve the performence of self join significantly.
