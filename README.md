pokémon-master
==============

An attempt to formulate an automatic pokémon player with Monte Carlo Tree Search. Interfaces with [showdown](https://pokemonshowdown.com/) to simulate games, build teams, etc.

# Goals
1. Given a team and a logged-in connection to a showdown server, select moves to execute which maximize chances of winning.
2. Given the valid pokémon and their movesets for a particular tier, generate a team with a good chance of winning.
3. Play against itself on a local showdown instance to train the search tree.

# License
[AGPL v3.0 **or any later version**](./LICENSE)
