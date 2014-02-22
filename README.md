Survival Game
============

A test game for learning C++. The idea is similar to Banished, but will
initially be played from the terminal and will be multiplayer. The current
focus is to get a simple version of the engine working before I delve into
anything more complicated. First up is the basic terminal interfacing and build
settings for the application.

Planning - Basic Class Map
--------

### Terminal Interfacing
+ data in
#### Renderer
+ menu
+ menu generator
+ renderer
### Game 
+ game loop
#### Villager
+ base villager
+ simple villager
#### Buildings
+ base building
+ storage
+ house
##### Farm
+ farm
+ potato
#### World
+ level
+ level generator
### Persistence
+ save
+ load
