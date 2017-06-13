This example is to test references from OPTs to Archetypes and how they are indexed by the EHRServer.

Many OPTs can have references to the same archetype nodes, and the nodes are loaded once, maintaining the references from many OPTs to each archetype node.
The archetype node index also has a reference to all the OPTs that use that node, so the relationship is many to many.