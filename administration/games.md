<!-- TITLE: Games -->
<!-- SUBTITLE: A quick summary of Games -->

# Available Game Types

There are 3 different type of games currently offered on the Platform.
| Available Game Types | | |
| ------ | ------ | ------ | 
|[ ![Lottorace Logo Large](/uploads/lottorace-logo-large.png "Lottorace Logo Large"){:height="100px" width="200px"} LottoRace Games](/administration/games/lottorace "Managing your Lottery & Raffle Games") | [![Weekly Lotto](/uploads/weekly-lotto.png "Weekly Lotto"){:height="100px" width="100px"}Lottery Games](/administration/games/lottery  "Managing your Lottery Games") | [![Daily Raffle](/uploads/daily-raffle.png "Daily Raffle"){:height="100px" width="100px"}Raffle Games](/administration/games/raffle "Managing your Raffle Games ")|





# Pre-loaded Game Templates
Depending on your installation type, we preload a number of pre-configured games for you.

You can use these pre-configured games, or Clone a copy to use as a starting point for your own custom game.

Each game template is assigned a unique Game Template ID (also called Game Definition ID).  This is differentiated from Game Instance ID which refers to an actual game, available to be played by players.


| |||
| ------ | ------ | ------ | 
| ![50 50 Small](/uploads/50-50-small.png "50 50 Small"){:height="100px" width="100px"} | ![The Daily](/uploads/the-daily.png "The Daily"){:height="100px" width="100px"} | ![Winner Take All Plus](/uploads/winner-take-all-plus.png "Winner Take All Plus"){:height="100px" width="100px"} |
| ![1 In 5 Winsplus](/uploads/1-in-5-winsplus.png "1 In 5 Winsplus"){:height="100px" width="100px"}  | ![1 In 3 Winsplus](/uploads/1-in-3-winsplus.png "1 In 3 Winsplus"){:height="100px" width="100px"} |  ![1 In 2 Wins Plus](/uploads/1-in-2-wins-plus.png "1 In 2 Wins Plus"){:height="100px" width="100px"}  |    
| ![Top 5 Win](/uploads/top-5-win.png "Top 5 Win"){:height="100px" width="100px"}  |  ![Weekly Lotto](/uploads/weekly-lotto.png "Weekly Lotto"){:height="100px" width="100px"}   | ![The Hourly Plus](/uploads/the-hourly-plus.png "The Hourly Plus"){:height="100px" width="100px"}
# Free Entry Sweepstake Games




# Creating Game Templates

To create any type of Game Templates, navigate to that game type (Raffle/LottoRace/Lottery) and look for the Create button on the top right corner.

 ![Create Lottery](/uploads/create-lottery.png "Create Lottery")

 

# Setting Game Schedules
### Repeat Count

### Available Hours

### Repeat Count

### Registration Start Delay

This value gives you flexibility to display and promote a game, while not permitting registration. 

I.e. New Years game which you want to promote, but not allow players to register yet.

available at  T = Registration Delay minus Start Time

If you want the registration to be available immediately, set registration delay to a very low number 1500 (milliseconds).

If you want to display a game for promotion, but not enable registration for 1 day before the Draw takes place, set the registration delay to 86400000.
Registration will not be available until 


### Registration End

This value enables us to disable new Ticket purchases  a few seconds before the start of the Tournament on the player web site. Its basically a timer on the last entry that can be purchased.

This is necessary so that the system can process and settle all pending transaction and close out game ledgers before the start of the Tournament.

The registration Delay should at least be one second (1000 milliseconds) for most games but should be set to 3 seconds with games with over 20,000 entries or more.


# Setting Game Logo/Branding

### Game Logo 
### Game Background 
### Playout Background 
### Tile Image  
### Tile Color 
# Starting & Stopping Games

### Starting Games

Press the Green Start Button to make the game Live on the site.

The game container should immediately appear on both the Play and Stream sites.

Registration will be available immediately for Instant Games and based on Registration Delay for Tournaments.


> **Usage note:** If there are any missing configurations, you will see "Incomplete Configuration" instead and get prompts to fix them.
{.is-success}

### Stopping Games

**To stop a game **

1. Set the game to Closed and wait for any open instances to finish
2. Press Stop

Pressing Stop will kill any open instances, cancel and refund all bets to player accounts, and prevent any new Game Instances from being created.

Only press Stop when there are no Game Instances  open for registration.

> **Usage note:**  Before stopping a game, set the game to Closed first and wait for open instances to complete
{.is-success}

### Setting a game to Closed status

This setting is used to gracefully shut down a Game. It prevents new Game Instance from being created. 

In the normal flow, when one Game Instance gets filled up or starts on a schedule, a new one is automatically created for other players to register in. 
Like an hourly game or an instant game that just filled up.

If a game is set to closed, the current Game Instance will be the last one and no new Game Instances will be created thereafter.  

> **Usage note:** Set the game to closed if you are planning to turn off the game, or as part of gracefully shutting the system down for maintenance and upgrades. 
{.is-success}
# Payout Simulator
# Viewing Past Game Instances
# Games Report





