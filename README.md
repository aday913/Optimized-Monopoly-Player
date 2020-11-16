# Optimized-Monopoly-Player
## Original Creator: Alexander Day

### Project Goal:
To both simulate a monopoly game and train a passably effective AI player

**Major Steps**:
- [ ] Create a game object that loads the spaces of the board (whose actions may be stored in another file), properties, cards, etc.
- [ ] Create a player object that holds all relevant attributes that a player would have in a real game
- [ ] Develop heuristic values that play objects can use to determine how to act (ie aggressive vs passive, etc.)
- [ ] Keep track of how players perform using objective values that describe their effectiveness during the game (ie max money, win/lose, etc.)
- [ ] Simulate large amounts of games, using gradient ascent/Metropolis-Hastings-like algorithms to tune the heuristic values
- [ ] Increase the difficulty of the players as more results are found to develop a better AI player
- [ ] *Optional:* Play against the AI player to further develop its heuristic values?
