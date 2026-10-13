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

## Current struggles

- Might have be strictly compiled for Windows machine
  - `/Assets/Script/InputManager.cs` throws errors when opening within Unity
  - `/Assets/XInputDotNet/Plugins/XInputDotNetPure.dll` might be the root of
    this problem
