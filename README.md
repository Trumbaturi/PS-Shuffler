# Shy's Pokémon Stadium Team Shuffler
This is a shuffler program that allows users to randomize their Pokemon Team for them to select in Pokémon Stadium 1, 2, or Pocket Monsters Stadium.
All the cups in each game are supported. In order to use the app, all you need to do is choose your settings then click randomize! You will receive 6 randomly chosen pokemon based on the applied settings. You may also click on individual slots to randomize that specific Pokémon.  
  
If you want to use this program on your Twitch stream, make absolutely sure before anything to crop the left side of the program by 193 pixels to get the cleanest output of the program for your livestream.
    
# Settings
When the app opens, the default settings are Pokemon Stadium 1, Gym Leader Castle / Poké Cup, No Sort.  
You have the following choices for the cups in each game.  
  
  Pocket Monsters Stadium:  
   Level 30  
   Level 50  

  Pokémon Stadium 1:  
   Prime Cup  
   Petit Cup  
   Pika Cup  
   Gym Leader Castle / Poké Cup 
  
  Pokémon Stadium 2:  
   Prime Cup  
   Little Cup  
   Gym Leader Castle / Poké Cup  
   
You may choose how the pokemon are sorted after they are randomized. For convenience, I recommend having Numerical Sort for Pocket Monsters Stadium and Pokémon Stadium 1 due to them not having any type of sorting feature aside from Pokédex number. Pokémon Stadium 2 has the ability to choose between Numerical or Alphabetical, the default is Alphabetical so in the end, do whatever is more convenient for you.  

# Custom Weighted Shuffles
Using the provided .csv as a base, you can also apply a custom weight to any cup of your choice. 

To use, click on the input button and select a compabitable .csv file. Once you import a file, the program allows you to toggle the ability to use custom weights.

You may put any integer values greater than or equal to 0 in any of the fields. The numbers do not represent the percentage odds, but rather how many tickets that Pokémon has. The more tickets they have, the greater chance they have in relation to everyone else. If you want to guarantee a Pokémon in the shuffler compared to others, give them a high amount like 99999. The provided "base.csv" has identical odds compared to the standard settings. You may use it as a base to create your own files for custom settings.

# Keyboard Shortcuts
Enter: Randomizes the Pokemon  
R: Toggle the program's orientation between horizontal and vertical  
I: Import a .csv file to apply custom weights to each of the cups  

Horizontal Mode:  
Number Pad 1: Randomizes the lower left Pokemon   
Number Pad 2: Randomizes the lower middle Pokemon   
Number Pad 3: Randomizes the lower right Pokemon   
Number Pad 4: Randomizes the upper left Pokemon   
Number Pad 5: Randomizes the upper middle Pokemon   
Number Pad 6: Randomizes the upper right Pokemon  

Vertical Mode:  
Number Pad 1: Randomizes the lower left Pokemon   
Number Pad 2: Randomizes the lower right Pokemon   
Number Pad 4: Randomizes the middle left Pokemon   
Number Pad 5: Randomizes the middle right Pokemon   
Number Pad 7: Randomizes the upper left Pokemon   
Number Pad 8: Randomizes the upper right Pokemon  

# Mord's Rental Hack
This shuffler also has compatability with Mord's Rental Hack (created by Mord_Fustang on romhacking.net) that allows for normally locked Pokemon to be playable in the Prime Cup. All you need to do is click the checkbox for this to take effect.
The following pokemon get replaced in the Prime Cups:

  Pokemon Stadium 1:  
   Metapod -> Mewtwo  
   Kakuna -> Mew  
  
  Pokemon Stadium 2:   
   Caterpie -> Lugia  
   Metapod -> Mewtwo  
   Weedle -> Ho-oh  
   Kakuna -> Mew  
   Magikarp -> Celebi  
    
   These romhacks can be found here and are Everdrive Compatable:
   
   Pokemon Stadium:
   https://www.romhacking.net/hacks/4460/  
   Pokemon Stadium 2:
   https://www.romhacking.net/hacks/4461/
   
# Side Notes  
You may also add your own custom images for the Pokemon. Just name the image the number of the Pokemon. For example for Mewtwo, call the image "150.png", or Charmander, "4.png", and replace the respective image in the "\img" folder. The dimensions of the image is 300 x 300. The default images were designed by me. The renders for the pokmeon were all sourced from the galleries of Bulbapedia.  

Whenever you reroll an individual Pokémon, the shuffler is guaranteed to not pick that Pokémon, even in custom settings where that pokemon may have 99999 entries compared to everyone else's 1.

I created this as a way for streamers to have a better layout for their streams whenever they do Gym Leader Castle randomizer runs. Plus as a cool trick, hold the enter key to make it so that the pictures cycle through quickly (same thing applies for the number pad keys). Perhaps add a drumroll sound effect for dramatic effect?

You can find me on Twitter: @TheNotSoShyGuy or Twitch: TheNotSoShyGuy.  
Icon drawn by Charlotte DeBoard.  

Special thanks to Ghoul02 for assisting in debugging the program and providing some additional ideas.

I hope you guys enjoy this shuffler program and if you have any questions or suggestions for future programs or fixes for this program, please contact me on Twitter, or by email TheNotSoShyGuy@gmail.com.
