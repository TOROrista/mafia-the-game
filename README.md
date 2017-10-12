# MAFIA: Card Play
> Mafia, also known as Werewolf, is a party game modelling a conflict between an two groups, the mafia, and the innocents/bystanders. At the start of the game, each player is secretly assigned a role affiliated with one of these teams. The game has two alternating phases: night, during which the mafia may covertly "murder" an innocent, and day, in which surviving players debate the identities of the mafia and vote to eliminate a suspect. Play continues until all of the mafia have been eliminated or until the mafia outnumbers the innocents.

The team aims to replicate this popular party game into a more accessible form of play. How do we convert such roles and mechanics into a web-based game?

Every game, a player is assigned a random role to play for a round where every game can be different.

#### `Mechanics`

A game is not allowed to start without having at least 7 players. The play starts of during the day, during which, a timer ticks down to signal the upcoming night. Each night, every player which has roles that can affect the gameplay (e.g MAFIA, Godfather, Doctor, etc.) will be __"woken up"__ and asked to their roles.

When the night timer stops, the game will cycle again to the morning in which players will try to accuse who the MAFIA are. This is a game of deception and lying, wherein you must do all you can to win, whether you are a MAFIA member or a member of the townspeople.

For further imformation on the roles that are available for this web-game, please refer to the [ROLES file](./roles/ROLES.md)

For asset contributions, please switch to the `art-branch` and when you create a pull request, direct in to the art-branch and not the `master` branch. Happy contributing! :confetti_ball:
