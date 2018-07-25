### TOP 10 MOST FREQUENT WORDS ARE:

the=33282
of=18016
and=12849
a=12717
to=12450
in=9387
was=7788
that=6601
he=6202
his=5529

### Try using a TreeMap instead of a HashMap. Does this make any difference?
Using a Treemap takes longer to conduct the tests than with a HashMap.

### What happens if you invoke countWords multiple times for different String iterators?
Because there is only one map it would all be placed on the same map.

### What crucial role does the Iterator abstraction play in making WordCounter testable?
The iterator abstraction allows entries to be added to the map. Otherwise it would be empty and therefor nontestable.