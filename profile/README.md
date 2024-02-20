![Image](./assets/banner.png?raw=true)

## 👨‍💻 developers
* Rick van Berlo  | [github](https://github.com/RickvanBerlo)

## 📖 introduction
This application will be a web application which profide end users to play party's they created.

End users can create a party with the editor that is provided with the desktop web application. 
Here they can select different task the player can play inside the party.
Some examples are:
* open questions
* closed questions
* spot the difference

and many more!

The creator of the party can start his own party so other players can join the lobby for playing.
the creator will automaticly be the partymaster of the party. He will have the suppervision of the party and can stop or continue the party as he like. He will also be the controller of some tasks. not every task can be handled by the computer. so if this is the case, the partymaster will be the decision maker of the task. The computer will give the partymaster his best guess which player had there task right or wrong.

in between tasks the creator can select if the party needs to contain a scoreboard. this scoreboard will let the players know how the ranking is at that moment.

Before you create your game, you will need to specify with type of party you would like to create. the differend types are:

* Single
* Groups

This way we can create games for player vs player and also for groups vs groups.
How many groups are needed for a party will be set in de editor of the party.
This information is important because, the creator need to specify if a task is only for 2 groups or more and which groups need to take part in the task.

The creator of the party will get 2 screens when starting a party. 1 screen wil contain all the information he needs to determine if a player or groups has answerd the task correct and will give the partymaster the power to continue the party, show the scorebord or abort the party completly. the second screen will show the curernt task information for the party. like the title of the task what the task is and will also show the scoreboard.

the player will play the game on the mobile or webapplication. they will get the correct input mechanic for the different task. if the player has finished his task he will get in a waiting state until he gets his following task. 

at the end of the party there will be a final scoreboard with shows the total points per player or group over the whole party.


## 🔨 services

This section will describe the services that will be implemented for making this web application. it wil explain what the name is of the service and the framework that will be used.

| service       | framework          | link                                         |
| ------------- | ------------------ | -------------------------------------------- |
| Frontend      | Vue                | [Frontend](frontend/README.md)               |
| Rest-api      | AWS Lambda         | [Rest-api](rest-api/README.md)               |
| Party Server  | Quarkus            | [Party Server](party-server/README.md)       |
| Database      | AWS DynamoDB       | [Database](database/README.md)               |
| Security      | AWS Cognito        | [Security](security/REAMDE.md)               |


## 🚀 V1
The first release of this application wil not contain every feature we have introduced in the upper sector.
The core functionality of this application wil be implemented for the first release. this means that we will only implement the following:

* Party Single
  * Open Questions
  * Scoreboard
* Party Screen
* Main Page
* Party Editor

With these component, a end-user can create a party which is playable.
The un-implemented features after the first release will be roll out in increments.


## 🙋‍♂️ Questions

* Do we need a intro for every item the first time they are playing the item in a party?
Think about mario party.



