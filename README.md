# Maximizing Extraction of Player Intent to Broaden Accessibility in Gameplay

## Overview

Modify an existing fighting game to allow:

1. Variable extension of the input-timing-window * Assists a user in difficulties
   of speed for executing complex input sequences
   - Complex Input Sequence - think Ryu from Street Fighter doing a "Hadouken"
     or "Shoruken"
2. Fuzzy matching of moves in the input buffer * Assists a user in difficulties
   of precision for executing complex input sequences

Each of these options work to extract more of a player's intent while playing,
and to reflect it within gameplay

## How will you store data?

Likely just text files where each line index is a frame of inputs,
logged from the game engine

I believe I should then be able to redirect input from the text files -> stdin,
as an independent variable to the dependent divergences of gameplay!
