.. _alias:

alias
=====

**Name**

``alias - set aliases``

**Synopsis**

``alias [-p] [name[=value] ...]``

**Description**

Alias with no arguments or with the -p option prints the list of aliases in the
form alias name=value on standard output.  When arguments  are  supplied,  an
alias is defined for each name whose value is given.  A trailing space in value
causes the next word to be checked for alias substitution when the alias is
expanded.  For each name in the argument list for which no value  is supplied,
the name and value of the alias is printed.  Alias returns true unless a name
is given for which no alias has been defined.
