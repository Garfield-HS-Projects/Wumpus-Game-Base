# Hunt the Wumpus
This is our implementation of the Hunt the Wumpus game!


## Code
Under the Htw directory is the Visual Studio solution file, along with the Htw project and the HtwTests project.

### The Htw project
The Htw project is broken up into different packages

#### common
This contains classes that are common across all objects, like the Direction enumeration (which needs to be filled in)

#### components
This contains the objects that you're assigned to (e.g. Cave, GameControl, etc.). 
Initially, it just contains an example component class.

#### forms
This contains any User Interface forms. 
Initially, it just contains the MainMenuForm.

#### Properties
This is where the game's embedded resources live (like images and sounds)


### The HtwTests project
The HtwTests allow you to make sure that your object is working as you expect. 
You'll write tests to validate your object's behavior.
Initially, it just contains an example test that create the Example component and validates the result of the Initialize method call.

## Samples
The samples directory contains some sample code to help develop the game
