# Rock-Paper-Scissors Assignment

## Requirements
- Visual Studio Code
- Github Copilot extension
- C# extension

## Tips
- You can write what you want your code to do by writing it in a comment (using // ). 
- You can also trigger a suggestion by using the 'Trigger Inline Suggestion' command in the command palette, or by using its hotkey (alt + / by default)

## Assignment (Step 1 - 3 already done)
- Step 1: Make a new folder called: RockPaperScissors and open it in Visual Studio Code
- Step 2: Right click the explorer on the left, and click "Open in integrated terminal"
- Step 3: Enter: ``dotnet new console --framework net7.0``
-- It will now create the necessary project files
- Step 4: Open Program.cs and replace the code with the following:
```
namespace RockPaperScissorsGame
{
    class Program
    {
        static void Main(string[] args)
        {
            // get the player name and create a new player object
            
            // greet player
           
            // create a new game object and pass it the player object
            
            // play the game
            game.Play();
        }
    }
}
```
- Step 5: Create a player object with the variable
``String : Name``
- Step 6: Create a game object with the variables
``Player : Player``
``Int : Wins``
``Int : Losses``
- Step 7: In the game object add the method Play()
-- In this method you will add the rock, paper, scissors logic
-- Ask for move input (rock, paper, or scissors)
-- Generate random move for the computer
-- Compare results
-- Add to wins/losses
-- Ask to play again
-- At the end of the game state the wins and losses
