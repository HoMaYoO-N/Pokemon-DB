# Pokemon-DB
A Pokemon database written in SQLite

Symbols different to those used in the course were used. They are as follows:

|Symbol|Meaning|
|---|---|
|\|\|| Participation: Mandatory-Cardinality: One|
|() <|       Participation: Optional-Cardinality: Many |
|\|  <|       Participation: Mandatory-Cardinality: Many |
|() \||       Participation: Optional-Cardinality: One|


We were interested in building a knowledge encyclopedia for the mainstream Pokémon games. This has the potential to be useful for any person playing said games, as it will be of great assistance to know where you can find certain things and what kind of things you can do in the games. Our encyclopedia must be rather extensive in order to do so. Therefore, we need information about entities such as Pokémon, their moves, game locations, gyms and trainers, as well as the relationships between them. A typical player will traverse many locations at the game, batting with other trainers (who could have special gym or leader four status as well) using Pokémon. Many Pokémon can be found at many locations and can be used by many trainers. Each gym is a special checkpoint in the game and has a leader and typically a specific type. The point of this application is to be as useful as possible for a game walkthrough and could allow a player to find information such as which Pokémon does a trainer battle with, what kind of moves are good to learn for a Pokémon, what kind of challenges a player can encounter when playing through a location, and so on. This information can be queried through single tables or by taking advantage of the existing relationships. This has the potential to be open-source too so that users can add new data for a game and it makes it easier than having one person fill everything in. This is a solution to the limitation of the fact that there is a LARGE amount of data to fill the tables with, too much for one person. For example, as of now, there are 742 moves and 809 species of Pokémon.
