<!-- TITLE: LottoRace Admin Guide-->
<!-- SUBTITLE: How create and manage LottoRace games -->


LottoRace is a player vs. player  multi-draw Raffle game that offers Guaranteed winners in every game.

LottoRace games can be played in Tournament, or Instant Game format with any number of entries (100K+).

All LottoRace games offer guaranteed wins; The draws continue until the entire prize pool is paid out to players.

Revenue is earned by charging a small Rake Fee on each entry.

You can use pre-configured games, or create your own unique games by tweaking any one of the many configuration paramaters available to you.

# Games
Here are some of the pre-configured games that are included in your Games Library.

| |||
| ------ | ------ | ------ | 
| ![50 50 Small](/uploads/50-50-small.png "50 50 Small"){:height="100px" width="100px"} | ![The Daily](/uploads/the-daily.png "The Daily"){:height="100px" width="100px"} | ![Winner Take All Plus](/uploads/winner-take-all-plus.png "Winner Take All Plus"){:height="100px" width="100px"} |
| ![1 In 5 Winsplus](/uploads/1-in-5-winsplus.png "1 In 5 Winsplus"){:height="100px" width="100px"}  | ![1 In 3 Winsplus](/uploads/1-in-3-winsplus.png "1 In 3 Winsplus"){:height="100px" width="100px"} |  ![1 In 2 Wins Plus](/uploads/1-in-2-wins-plus.png "1 In 2 Wins Plus"){:height="100px" width="100px"}  |    
| ![Top 5 Win](/uploads/top-5-win.png "Top 5 Win"){:height="100px" width="100px"}  |  ![1 In 4 Wins](/uploads/1-in-4-wins.png "1 In 4 Wins"){:height="100px" width="100px"}   | ![The Hourly Plus](/uploads/the-hourly-plus.png "The Hourly Plus"){:height="100px" width="100px"}

## Tournaments vs. Instant Games

LottoRace games can be configured as either InstaPlay instant Games, or Tournaments.


**Tournaments start at a specific date and time**  and can have any number of entries.

**InstaPlay instant Games Starts as soon as the game is full.**


![Tourney Insta](/uploads/tourney-insta.png "Tourney Insta")

## Common Settings

Although there are nearly [50 different configuration parameters](/administration/games/lottorace#advanced-settings) at your disposal, in most cases you only need to change a few key elements to create a unique game.

### [Buy-in & Rake](/administration/games/lottorace#set-buy-in)

This determines how much of the Entry Fee is charged as Rake Fees, and how much goes into the prize pool to be won by players.

It is an important factor which determines profitability for you, and the attractiveness of the prize pool for the player.

### [Odds of Winning & Payout distribution](/administration/games/lottorace#set-odds-of-winning)

Odds can be set in a number of ways for Tournaments and Instant Games.

> Tournament Odds
{.is-info}

1) Fixed Number of Winners:  1, 3, 5, 10, etc..
2) As a Percentage of Plays: 1 in 5

> Instant Game Odds
{.is-info}

Instant Games can have odds as follows:

3) 1, 3, 5, 10, 30, 50, 100 Winners:

This can determines if the game is risky (1 in a million wins)  with large payouts ($1 for a chance at $1M), or less risky with average payouts.  
You can offer Winner Take All game for the risk loving, offering one prize for a field of 100,  or a 1 in 5 Wins game for the risk averse, where there are 20 prizes for a field of 100. 

> **Usage Note:** The odds can also factor into how many lines a player should be able to purchase. 
For example if the odds are 1 in 5, you should allow the player to purchase at least 5 lines so that on average there is at least one positive experience for the player. 
{.is-success}



### [Pick Size & Range](/administration/games/lottorace#pick-size)

Easily create any type of game like a 5/35 where the player picks 5 numbers between 1 and 35.

The pick size impacts the speed of the game and the overall gaming experience of players.

For example if you have a large range and few entries, like pick 6 between 1-49, then it will take many draws before all the prizes are paid out and it could be a long and somewhat boring game.

If you have a small range, like pick 5 between 1-10 combined with a  large number of entries, then the game will finish in very few draws and there will be many shared prizes.

> **Usage Note:** If a  [Progressive Jackpot](/administration/games/lottorace#progressive-jackpot) is added to the game, then the Jackpots odds will implicitly mirror the Pick Size and Range.
{.is-success}

> **Usage Note:** You can also specify  [Bonus Pick](/administration/games/lottorace#bonus-pick) ranges to increase the odds for Jackpots or Lottery games alike.
{.is-success}

### [Min/Max Plays Per Game](/administration/games/lottorace#min-max-entries-per-game) 

The Min and Max play limits enable you to create games of various sizes.  I.e. a 12 player instant game or a 180 player instant game. A tournament with at least 100 participants, or a tournament with no minimum.

Aside from the obvious impact on size, this settng can impact tournaments Prize Pools and wait time between games for instant games.

#### Tournaments
The minimum ticket limit can be used in conjunction with a guaranteed prize pool in order to ensure that the minimum number of tickets are sold to cover the Guarantee.
If the minimum number of entries is not sold, the game can either be set to automatically rescheduled or be cancelled and all bets refunded.


#### Size of Instant Games

In any Instant Game, all the entries must be sold before the game can start. Therefore,  the bigger the game is, the longer players have to wait before all the lines are sold.

These limits can impact the overall experience for players and should therefore take into account traffic volumes and player expectations.

> **Usage Note:** Less is more. Having less games focuses the traffic into fewer games which leads to higher prize pools for tournaments and quicker starts for Instant Games. 
{.is-success}

> **Usage Note:** We recommend having Instant Games with 2, 6, 9, 12, 20, 50, 180, 360 Entries, based on traffic volume.
{.is-success}

> **Usage Note:** Have fewer tournaments, and schedule them for peak times.
{.is-success}


## **Advanced Settings**

Here are the rest of the available configuration parameters.

You do not need to adjust the default configurations and should only do so with care.

### Game Related Configuration

| Game Configuration |||
| ------ | ------ | ------ | 
| [Odds of winning](/administration/games/lottorace#set-odds-of-winning) | [Buy-in](/administration/games/lottorace#set-buy-in) | [Rake Fee](/administration/games/lottorace#set-rake-fee) |
| [Pick Size](/administration/games/lottorace#pick-size) | [Bonus Pick](/administration/games/lottorace#bonus-pick) |  [Tournament vs. Instant](/administration/games/lottorace#tournaments-vs-instant-games) | 
|   | [Payout Formula](/administration/games/lottorace#payout-formula) |  [Estimated  Prize Pool](/administration/games/lottorace#estimated-prize-pool) | 
| [Guaranteed Prize Pool](/administration/games/lottorace#guaranteed-prize-pool) | [Multi-Currency](/administration/games/lottorace#set-currency) | [Seed Prize Pool](/administration/games/lottorace#prize-pool-seed) | 
| [Min/Max Plays Per Player](/administration/games/lottorace#min-max-entries-per-player) | [Min/Max Plays](/administration/games/lottorace#min-max-entries-per-game) | Subscription | 
| Prize Roll Over | Failover Handling | Shared Games |   
| [Schedule](/administration/games#setting-game-schedules) | [Repeat Count](/administration/games#repeat-count) | [Available Hours](/administration/games#available-hours) |
|  | [Registration Delay](/administration/games#registration-delay) | [Closeout Period](/administration/games#closeout-period) | 
| Multilingual | HTML Description | Rules text |
| [Ball & Draw Speed](/administration/games/lottorace#ball-draw-speed) | [Narrator Voice](/administration/games/lottorace#game-narrator) | [Live Sorting](/administration/games/lottorace#client-sort-order)  |
| [Game Logo](/administration/games#game-logo) | [Game Background](/administration/games#game-background) | [Playout Background](/administration/games#playout-background) | 
| [Tile Image](/administration/games#tile-image)  | [Tile Color](/administration/games#tile-color) ||



### Progressive Jackpot Settings

| Progressive Jackpot |||
| ------ | ------ | ------ | 
| [Initial Balance](/administration/games/lottorace#initial-balance) | [Matches Required](/administration/games/lottorace#required-matches) | [Eligible Draws](/administration/games/lottorace#eligible-draws) | 
| [Progressive Fee](/administration/games/lottorace#progressive-fee) |  [Reserve Fee](/administration/games/lottorace#reserve-fee) | [Reserve Multiplier](/administration/games/lottorace#reserve-multiplier) |  



### Loyalty Points & Rewards

| Loyalty Points & Rewards |||
| ------ | ------ | ------ | 
| [Loyalty Currency](/administration/games/lottorace#loyalty-currency) | [Earned Per Entry](/administration/games/lottorace#points-per-entry) | [LuckyBall Reward](/administration/games/lottorace#lucky-ball-reward)
| [Number of Lucky Balls](/administration/games/lottorace#number-of-lucky-balls) | [Multi-Win Reward](/administration/games/lottorace#multi-win-reward)|  [Bonobo Reward](/administration/games/lottorace#bonobo-reward) | 
| [Perfect Game Reward](/administration/games/lottorace#perfect-game-reward) |   [Active Status](/administration/games/lottorace#active-status) ||



# Revenue Model 
## How to Earn Fees (Rake)

Revenue is earned by charging a Fee on every entry.




### Rake Fee

The **Rake Fee**  is earned by the Operator (less any **Progressive Jackpot** contribution if applicable).


The Rake Fee is set along with the Buy-in, when creating the game.

The Player is able to see the breakdown on the confirmation page which displays the Buy-in, Rake Fee and Jackpot Contribution as shown below.

![Fee Breakdown](/uploads/fee-breakdown.png "Fee Breakdown")

> **Usage Note:** Any Jackpot Contribution and Jackpot Reserve fees are taken out from the Rake Fee.  For example if the Rake Fee is set to $0.50 and Jackpot Contribution and Reserve are $0.05 and $0.02 respectively, then the actual Net Rake per entry is $0.43.   
{.is-warning}



## Return to Player

The **Return to Player (RTP)** is an important measure of how much is actually paid back to the players in prizes in an average game.

The RTP of each LottoRace game can be calculated as  ***Buy-in/(Buy-in + Rake)***

For example a game where the Buy-in is $10 and the Rake is $1 has an RTP of  10/(10+1) = 90.9% 


> **Use Case:** Highlighting the higher than average RTP  of LottoRace games. 
{.is-success}

> **Usage note:** An average LottoRace player buys 20-30 entries spread over 10-15 games in a session, most of them in InstaPlay games. If the Rake is 10%, then on average, the player will lose one Entry fee, every 10 entries. Due to this high turn over its important that the Rake is not so high such that the players entire bankroll is taken as fees in few games. To extend the players entertainment value we recommend a Net Rake of no more than 10%.
{.is-success}


# Buy-in, Prizes & Odds

### Entry Fee


The **Entry Fee** paid by the player for each LottoRace entry consists of a **Buy-in** and **Rake Fee**.

The total Entry Fee (Buy-in + Rake) is displayed on all top level pages to provide clarity with respect to total cost for the player.

![Entry Fee](/uploads/entry-fee.png "Entry Fee")

> **Use Case:**  Shown on top level navigation for each game 
{.is-success}

## Setting Buy-in & Rake



### Set Currency

The Primary currency of the game, in which all prizes and payouts are denominated in.

The primary Buy-in currency must be the same as this Currency.




### Set Buy-in
 
The **Buy-in**  is contributed entirely to the Prize Pool and is guaranteed to be won in the game.

The Buy-in is critical when determining the target Prize Pool of the game which determines its overall attractiveness.

![Buy In Rake](/uploads/buy-in-rake.png "Buy In Rake")

> **Use Case:** If the Buy-in is set to $10 and your maximum entries are 1000, then your Prize Pool will be a maximum of $10,000
{.is-success}

### Set Rake Fee

The **Rake Fee**  is earned by the Operator (less any **Progressive Jackpot** contribution if applicable).


### Secondary Currency

The secondary currency of the game which can be used for Buy-ins.

> **Use Case:**  Loyalty Currency:  "Enter with $2 or 200 Loyalty Points."
{.is-success}
## Payout Tables & Odds

The minimum number of winning bets in a game. For Tournaments its expressed as 1 in X number of bets. For Instant Games and Fixed Payouts its expressed as the actual number of winners. 

For 1 Draw games its expressed as the number of matches required to win a prize.
Prize Pool - The prize pool available in the game


### Set Odds of Winning

### Payout Formula

#### Tournament Payout Formula

#### Fixed Winners

#### Instant Games Payout Formulas

### Guaranteed Prize Pool

This setting is used to guarantee a minimum value for the prize pool.

If the sum of all the Buy-ins do not equal or exceed this value before the start of the game, the prize pool will be supplemented by the difference.

If the sum of all the Buy-ins exceed this value before the start of the game, no additional supplements are made to the prize pool.

> **Use Case:**  The Guaranteed prize pool is displayed to players from the moment that the game is turned on . If the actual prize pool exceeds the guaranteed prize pool then the prize pool which is displayed to players will increment up by the value of the Buy-in for each entry thereafter.
{.is-success}

> **Usage Note:**  If the Guaranteed prize pool is $1000 and only $900 in buy-ins have been contributed, then an additional $100 is contributed from Guaranteed Games Expense account to the prize pool of the game.
{.is-success}

### Estimated Prize Pool



### Prize Pool Seed

### Estimated Players
# Basic Configuration

### Pick Size 


Defines the number range and the pick size for each game. 

For example a 5/20 Game is defined as Pick 5 numbers between 1 and 20.
Games can have a pick range up to  6 numbers between 1 and 60.

![Pick Size](/uploads/pick-size.png "Pick Size")

### Bonus Pick 


### Min/Max Entries Per Game

> Minimum Entries
{.is-info}

The minimum number of entries that a Tournament must have in order to start.  This value should take into account the number of prizes available or the Guaranteed prizes.

> Maximum Entries
{.is-info}

The total number of entries avaialble for sale in game.
In **Instant Games** the max and min are the same since Instant Games always start when all the available entries are sold.

> **Usage Note:** You have a tournament where there is a fixed number of prizes, i.e. 5;  then the minimum number of entries must be at least 5. 
{.is-success}





### Min/Max Entries Per Player





### Allow Subscriptions
# Progressive Jackpot



## Jackpot Settings


### Initial Balance

The initial balance of the Jackpot.

This amount is funded by debiting the Jackpot Reserve account

When the game is turned on for the first time, expect the Jackpot Reseve Account to go into the negative by the same amount as the Jackpot Initial Balance.


### Jackpot Balance

Balance of the Jackpot at this moment in time. 

### Jackpot Reserve

Jackpot Reserve is the account which funds the Initial Balance of the Jackpot when its first started or after it has been won.

When the game is turned on for the first time, expect the Jackpot Reseve Account to go into the negative by the same amount as the Jackpot Initial Balance.

As each entry is placed, an amount equal to the Jackpot Reserve fee is taken from the Rake and credited to the Reserve Account. 

This process gradually replenishes the Reserve account so that the initial balance can once again be funded when the Jackpot is won.

The amount collected in the Reserve account can be controlled and managed by the Reserve Multiplier setting.


### Required Matches 

The number of balls that must be matched in ONE single draw out of the total pick size. 

6/6 means match all 6 numbers in one draw to win the Jackpot.


> **Use Case:**  You can make the jackpot easier or harder to hit by adjusting this setting. For example match only 3 out of 6 to win the Jackpot is much easier than matching all 6 to win.
{.is-success}



### Eligible Draws

 The number of draws in which the Jackpot can be won. For example if set to 2, the bet must match the required number of matches in the first 2 draws to be eligible to win
Fee (Reserve) - The amount which is contributed to the Jackpot.  The amount which is contributed to the Jackpot Reserve

### Progressive Fee 
### Reserve Fee

The amount which is contributed to the Jackpot Reserve


### Reserve Multiplier

The Reserve mutliplier lets you decide when to stop collecting the Reserve Fee (and leave it in Rake instead) based on how much is accumulated in the Reserve Account in relation to the Initial Balance.

For example

> **Use Case:**  Setting this to 3 would enforce the collection of the Reserve Fee up to the point where the Reserve Balance is 3x the Initial Balance
{.is-success}



## Odds & Math



# Advanced Settings Only

### Ball & Draw Speed

This setting allows you to control the number of seconds between each ball drawing and consequently the games' pace and speed.

The recommended value for Tournaments  are 3000 ms and 7000 ms for ball and draw delay respectively.

The recommended value for Instant games  are 2250 ms and 5000 ms for ball and draw delay respectively.


> **Use Case:** For an ultra faced paced game combine very fast Ball and Draw Delays (1500/5000) with very small number ranges (Pick 3/10) to product a quick, instant satisfaction game. 
{.is-success}


### Game Narrator

The game narrator which calls out the numbers as they appear.

Male and Female version with an English accent are currently available.

*Custom narrators can be added upon request.*


### Client Sort Order

The order in which the game is displayed on the client

### Fail Strategy 

# Loyalty Points & Rewards
## Loyalty Points
### Active Status 
### Loyalty Currency 
### Points Per Entry 

##  In Game Rewards 
### LuckyBall Reward 
### Multi-Win Reward
### Bonobo Reward  
### Perfect Game Reward 
### Number of Lucky Balls 

