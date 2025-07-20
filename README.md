# Monogame setup

I created this repo as a simple directory structure to help people get right into things with building a game in MonoGame. This repo contains everything I need to get started building a game, and it may also help you in case you are unfamiliar with the dotnet sdk or monogame. 

## Features (if you can call it that)

- Pre-made directory structure so that you don't have to think too much about all of that
- A gitignore (based on the dotnet gitignore)
- Four linked projects for your Engine, Core (game), Tests and Tools. 
- Clean build solution by storing Intermediate (obj) and Executable (bin) files in an ignored Build directory
- Some suggestions for directories you may want to consider using in making a game. 

## Directories

- Assets -- Place to store all raw assets used in your game. Kept seperate from your code. 
- Build -- Directory where all build files will be placed, so that they don't clog up your working directories. 
- Core -- The main directory where your Game logic will reside. Based on the msgdesktop template for monogame. This contains:
- - Configs -- For the configuration of your game
- - Content -- The monogame content loaded into your game
- - Data -- Data stored for your game
- - Scripts -- Scripts used in your game
- - Src -- The source code of your game
- Docs -- Directory for your documentation, design documents (and perhaps also story)
- Engine -- The directory for your game engine. Seperated from the rest of the game so that it can be easily reused. 
- Tests -- Your test suite for your game. 
- Tools -- Any tools you may want to create, like level editors or the likes. 

## Final note and disclaimer
Note that this project is mostly for personal use. I am self-studying game programming, and wish to make it easier for myself and others to get going with building a game from scratch. After a few small games in monogame, I have found this to be quite a nice directory structure, but it may not work for everyone. 

If you have questions or suggestions for how to improve this, feel free to reach out to contact@paulstapel.com. 

