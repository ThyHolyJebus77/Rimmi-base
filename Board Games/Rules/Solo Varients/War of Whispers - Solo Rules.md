# `=this.file.name`

## Introduction

This solo variant allows you to play War of Whispers against one or two AI opponents (bots). The bots simulate the actions of other players, providing a challenging and engaging experience while maintaining the core mechanics and theme of the original game.

## Setup

1. Choose your difficulty level:
   - Easy: Standard bot scoring
   - Medium: Bot score +1 for each card stored
   - Hard: Bot score +2 for each card stored

2. Select the number of bots (1 or 2) and their types:
   - Order of Madness (OoM): More unpredictable
   - Glory Hounds (GH): Focuses on controlling cities

3. Set up the game board, cards, and armies as per the normal game rules.

4. Choose your faction and place 5 loyalty tokens with the empire side up above their respective places on your faction board. (These will be placed on the board during the Swap phase.)

5. Set up the bot faction(s):
   - Order of Madness: Place 5 loyalty tokens face-down on their respective places.
   - Glory Hounds: Place 5 loyalty tokens empire-side up on their respective places.

6. For Order of Madness: Swap the Devout and Opposed tokens to the empire side. (Tokens to the right of Devout will be swapped to the empire side each subsequent turn.)

7. Prepare the bot agent placement guide (see Agent Phase section).

## Game Round Structure

Each round consists of four phases: Agent, Empire, Swap, and Cleanup. The game lasts for 4 rounds.

### Agent Phase

1. Agent Removal (from Round 2 onwards):
   - 1 bot game: Remove 2 of your agents and 1 bot agent (3rd and 4th from previous round)
   - 2 bot game: Remove 1 of your agents and 1 bot agent (3rd from previous round) from each bot
   - For Glory Hounds: Always remove the sheriff first and the steward second

2. Bot Agent Placement:
   - 1 bot game: Place 4 bot agents
   - 2 bot game: Place 3 agents for each bot
   - If a designated space is occupied, place the agent in the next lower position

Use the following placement guides:

#### Order of Madness Placement Guide

Round 1:
1. Devout empire Chancellor
2. Devout empire Marshall
3. Opposed empire Sheriff
4. Empire next to Devout empire Sheriff (clockwise on the empire wheel)

Round 2:
1. Devout empire Steward
2. Dutiful empire Chancellor
3. Opposed empire Steward
4. Empire next to Devout empire Steward

Round 3:
1. Dutiful empire Marshall
2. Affiliated empire Chancellor
3. Opposed empire Marshall
4. Empire next to Devout empire Marshall

Round 4:
1. Dutiful empire Steward
2. Affiliated empire Marshall
3. Unallied empire Chancellor
4. Empire next to Devout empire Chancellor

#### Glory Hounds Placement Guide

Always place agents in this order:
1. Chancellor of Devout empire
2. Marshall of Dutiful empire
3. Steward of Affiliated empire
4. Sheriff of Unallied empire (only in 1 bot game)

3. Your Agent Placement:
   - 1 bot game: Place 3 agents
   - 2 bot game: Place 2 agents

### Empire Phase

Resolve empire actions as normal, with the following bot priorities:

1. Attack
2. Add Armies
3. Take Card
4. Switch Position

#### Bot Attack Priority

- Never attack empty regions
- Target empires lower in the bot's loyalty hierarchy
- Attack order: city > farm > fort
- Only attack if victory is guaranteed and exactly one army can move to the region
- If the attacking empire has hidden loyalty (OoM), attack any empire except the most loyal
- If attacking an opposed empire, retreat armies from the region with the most units (leaving 1 unit) to the closest empty region. If no empty region is available, move to a region with a city. If neither option is available, move to the region with the least units (choose randomly if tied).

#### Bot Army Addition Priority

- Never add armies to empty regions
- Secure cities first
- Reinforce border regions with buildings (up to 4 armies, 6 with a farm)
- Place remaining armies in cities
- Prioritize placing armies far from more loyal empires

#### Bot Card Taking

- Take cards and store them on the bot's faction board (removed from the game)
- Bots have no hand limit during the game and can store any number of cards

#### Bot Position Switch

- Remove 1 enemy unit from every region bordering the active empire (prioritize removing units from less loyal empires)

### Swap Phase

1. Perform your loyalty swaps as per normal rules

2. Bot loyalty swaps:
   - Order of Madness: Swap the leftmost hidden loyalty token to the empire side
   - Glory Hounds: 
     a. Switch the empire with the most cities to 2 positions left (or to the most loyal position if already leftmost)
     b. Move the empire with the second-most cities 1 position left (unless it would switch with the first empire)

3. Update the round marker

### Cleanup Phase

Proceed as in the normal game. Bots can have more than 5 cards in their pile.

## Game End and Scoring

The game ends after 4 rounds. Calculate scores as follows:

1. Count your points normally
2. Count bot points:
   - Easy mode: Standard scoring
   - Medium mode: Add +1 for each card stored by the bot
   - Hard mode: Add +2 for each card stored by the bot

The highest score wins!

## Additional Rules and Clarifications

1. Tiebreakers: When the bot has multiple valid options, choose randomly or the option that seems most detrimental to you.

2. Hidden Information: For Order of Madness, keep their loyalty tokens hidden until revealed. For Glory Hounds, all loyalties are visible.

3. Multi-bot Games: In 2-bot games, alternate which bot goes first each round.

4. Card Effects: When a bot uses a card effect, apply it in a way that most benefits the bot's current strategy or hinders your position.

5. Negotiation and Voting: Skip any mechanics involving negotiation or voting between players.