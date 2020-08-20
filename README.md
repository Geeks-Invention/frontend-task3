# frontend-task2

## Basketball team manager

Create a small application which can:
- add players to a basketball team (only one team exists);
- select 5 players from the team who will play in the first quarter of the game.

1. Compose Team
Each player can take only 1 of 5 positions during the game but can have skills and talents to play in different positions.
Here is the required information to add player to the team:
- First Name (required string);
- Last Name (required string)
- Height (required positive number)
- Position (required one or more to be selected)
And the list of all positions: the point guard (PG), the shooting guard (SG), the small forward (SF), the power forward (PF), the center (C)

2. First Quarter
During the game on a court can be 5 players from each team. We need to select 5 players and assign to each his role during the match. Note that:
- players can not appear multiple times;
- roles also should be unique;
- a role can be set to a player only if there is skill or talent to play it.

Validation
In case of any invalid input:
- Controls with error should be highlighted;
- Error message with details should be displayed next to the field.

![Example layout](https://i.ibb.co/9TSYrQs/Screenshot-2020-08-19-at-1-12-15-PM.png)
