# FindLooking
A data pack that can be used to get the entity that a player is looking at by calling a predicate with the `looking_at` player condition.

# Usage:
1. add the tag `find_looking.candidate` to all entities that should be possible to find
2. call the function `find_looking:find` as the player
3. The entity that the player is looking at will be marked with `find_looking.result`
