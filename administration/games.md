<!-- TITLE: Games -->
<!-- SUBTITLE: A quick summary of Games -->


## Welcome to Game Management


### Overview

The betting platforms organizes games into Game Definitions and Games Instances.
A Game definition consists of the rules, naming, branding and configurations for each game. A Game Instance is a specific instance of the game, built on the game definitions of the game which is available for players.

To view the available games complete the following steps:

# Log in to your Admin section
# Navigate to the Games List tab of the Admin

#### Accessing Games List

The Games List is your first stop for managing your games. 

From the games list you are able to see all games in the system and their respective status.

To expand the details for each game, click on the arrow icon located on the right of each game row.

[[File:Admin_games_list.png]]


==== Data Displayed ====

| Features | Description | Usage notes |
| ------ | ----------- | ----------- |
| Logo, Name(ID) | Displays the game logo, it's name and the Game Definition ID. | Please note that Game Definition ID is not the Instance ID. Game definitions will have multiple game instances which inherit the configurations of the Game Definition. | 
| X/Y | Denote the configured pick size and range for the game. For example, 6/49 means pick 6 balls between 1 and 49. | N/A
| $X/Y | Displays the rake and buy-in for each game.  | N/A |
| Game Type (Interval) | Denotes game type: Tournament or Instant Game. If the game is of tournament type, the frequency of each game is also shown. | N/A |
| X Open | Denotes the number of Open Instances of this game | Clicking on this link will list the open games for this game definition. |

=== Action Buttons ===

| Buttons | Action | Usage notes |
| ------ | ----------- | ----------- |
| Close/Open | Setting a game to close will restrict any new game instances from being created. Can be used at any time and no prerequisite actions are required. | Typically used as part of game shutdown procedure. If a game is closed and no open instances exist, then setting the game to Open will not automatically create new instances. The game must be stopped and started. |
| Stopping a Game | Stopping a game will stop any open instances and refund all bets. Should only be used when there are no open instances available and after all games in play have been completed.  | Before stopping a game, set the game to close first. Setting it to close will ensure no new instances are created and you can wait for any existing games to finish before stopping a game. |
| Starting a Game | Starting a game will create a new open instance of the game definition.  | N/A

== Starting & Stopping Games ==

Refer to action buttons above.

== Game Configuration Overview ==

To view all configurable options for a game, click on the arrow on the right of each game row to expand.


The following sets of information are displayed for each game. Some of the configurable options can be edited using this interface and are discussed below. For changes to other configurations, please contact us. 


[[File:Admin_game_definition_details.png]]

== Game Configuration Options ==

[[File:Admin_game_configuration.png]]


=== Config Values ===

| Value | Description | Usage notes |
| ------ | ----------- | ----------- |
| Type | Tournament or Instant Game | Tournaments start at a specific time. Instant games start when they are full and not on a schedule. |
| Game Rule | Defines the rules of the game. Can be any of the following:<br/>
* Regular Game
* Elimination
* OneDraw | N/A |
| Game Playout | Defines the visual presentation of the game. Can be any of the following: * LottoRace * LottoRace2 * PokerRace * SlotsRace | N/A |

|- style="text-align: left;"
| Pick ||Defines the number of balls which are to be picked and the set of numbers from which they are picked. For example in a 6/49 game you would pick 6 numbers between 1 and 49  || N/A
|- style="text-align: left;"
| Draw Limit || Used to guard against excessive number of draws in a game. Once the game reaches this number of draws, it will randomly select a winner for each subsequent draw until all the prizes are paid out.|| Should be greater than 3 and lower than the Jackpot threshold.
|- style="text-align: left;"
| Manual Bet || If true, it enables the player to manually pick numbers for the game|| Can be true or false
|- style="text-align: left;"
| Live Sort || If true, it enables sorting of the All Bets section (Multimedia Screen) after each ball (vs. after each draw) || Can be true or false
|- style="text-align: left;"
| Fail Strategy|| A game must meet the minimum number of players in order to play. In the case of tournaments, if the minimum number of bets is not reached by the scheduled start time, then the game has failed and will either be rescheduled or refunded. || Can be set to re-scheduled or refund.
|- style="text-align: left;"
| Minimum Bets|| The minimum number of bets a game must have in order to play. In the case of Instant Games the minimum number is equal to the maximum number. In the case of tournaments it can be set. || Should be greater than the number of guaranteed places paid.
|- style="text-align: left;"
| Estimated Bets || The estimated number of bets in the game. This effects the behavior of Prize Pools shown throughout the game. Once the number of Bets reaches or exceed this number, then the actual prize pool is shown. || N/A
|}

== Game Scheduler ==
[[File:Admin_game_schedule.png]]

=== Config Values ===

{| class="wikitable" style="border-spacing: 2px; border: 1px solid darkgray;"
! style="width: 15%;" | Value
! style="width: 50%;" | Description
! style="width: 35%;" | Usage notes
|-
|- style="text-align: left;"
| Start Time || The time at which a tournament starts.|| Tournaments start at a specific time.  The first tournament instance will open, even when the game is turned on, at the the specified time start time.
|- style="text-align: left;"
| End Time || The time at which no new open instances will be created.|| N/A
|- style="text-align: left;"
| Next Fire Time || The next scheduled open game || N/A
|- style="text-align: left;"
| Repeat Interval || Defines the period between each game.|| For example, if a game interval is every hour, then the game instance will run every hour and a new game instance will automatically be created at the same time.
|- style="text-align: left;"
| Repeat Count || The total number of instances which the game definition can have. No new instances will be created once this number is reached || N/A
|- style="text-align: left;"
| Available from || Determines the hours of the day, in which the game is available in || Can be used to schedule two different games at two different times of day, but setting one game definition to cover the first x hours, and the second game definition to cover the rest of the hours in the day.
|- style="text-align: left;"
| Tournament Type || Only impacts sorting of tournaments and determines their grouping into Daily, Weekly or Hourly tournaments.  || N/A
|- style="text-align: left;"
|}

== Jackpot Configuration ==

[[File:Admin_jackpot_configuration.png]]


=== Config Values ===

{| class="wikitable" style="border-spacing: 2px; border: 1px solid darkgray;"
! style="width: 15%;" | Value
! style="width: 50%;" | Description
! style="width: 35%;" | Usage notes
|- style="text-align: left;"
| Match Rule/Matches Needed || The number of balls needed to match in ONE single draw out of the total pick size. i.e. 6/6 means match all 6 numbers in one draw to win the Jackpot || Only the number of matches is specified. The pick size is specified in the game configuration.
|- style="text-align: left;"
| Eligible Draws|| The number of draws in which the Jackpot can be won. || For example, if set to 2, the Jackpot can only be won in the first 2 draws.
|- style="text-align: left;"
| Trigger Threshold || The amount after which the Jackpot is randomly triggered for a random bet. || Expressed in the primary currency of the game. Should always be higher than the initial balance.
|- style="text-align: left;"
| Trigger Odds|| The randomization factor for a Jackpot. || Expressed as in integer. For example, If Trigger odds is set to 25 and if Jackpot trigger is at $100 and the Jackpot is now at $101, then there is a 1 in 25 chance on each draw, that the jackpot will be won by a random bet.
|- style="text-align: left;"
| Reserve Multiplier|| The multiple of the Initial Balance that must accumulate in the Reserve Balance before the reserve fee is no longer taken from the Bet Fee || Expressed as an integer. Should typically be  be between 3 and 5
|- style="text-align: left;"
| Progressive Fee|| The amount which is taken from each Bet fee that contributes to the Jackpot Progressive of that game.  || Expressed in the primary currency of the game, in nominal terms. Typically equal to 2.5% of the bet value (5 cents in a $2 game, expressed as 0.05)
|- style="text-align: left;"
| Reserve Fee|| The amount which is taken from each Bet fee that contributes to the Jackpot Reserve of that game.  || Expressed in the primary currency of the game, in nominal terms. Typically equal to 0.5% of the bet value. (1 cent in a $2 game, expressed as $0.01)
|- style="text-align: left;"
| Initial Balance|| The initial balance of the Jackpot which is funded via the Jackpot Reserve account.|| Expressed in the primary currency of the game. Should typically be around $100
|- style="text-align: left;"
| Balance(Reserve)|| Balance of the jackpot at this moment in time. Balance of the Jackpot Reserve at this moment in time. || N/A
|- style="text-align: left;"
|}

== Prizes & Buy-in ==

[[File:Admin_game_buyin.png]]


=== Config Values ===

{| class="wikitable" style="border-spacing: 2px; border: 1px solid darkgray;"
! style="width: 15%;" | Value
! style="width: 50%;" | Description
! style="width: 35%;" | Usage notes
|-
|- style="text-align: left;"
| Prayout Currency || Tournament or Instant Game || Tournaments start at a specific time. Instant games start when they are full and not on a schedule.
|- style="text-align: left;"
| Buy-In/Rake (CUR)  || Primary currency Buy-In Option|| N/A
|- style="text-align: left;"
|Buy-In/Rake (CUR) || Secondary currency Buy-In Option || N/A
|- style="text-align: left;"
| Winner Ratio || The number of winners || Usage varies based on payout formula used. Expressed as a percentage  for all games except Fixed Winner Payout. 
|- style="text-align: left;"
| Payout formula|| || N/A
|- style="text-align: left;"
| Prizes|| the prizes pool which is shown for the game. || The amount displayed depends on the Estimated or Guaranteed settings.
|- style="text-align: left;"
| Prize Type: || Estimated or Guaranteed. || N/A
|- style="text-align: left;"
| Minimum Bets|| The minimum number of bets which are required for the game to play || Should always be larger than the number of prizes available.
|- style="text-align: left;"
| X Estimated|| Number of Estimated Players in the game. || N/A
|}
