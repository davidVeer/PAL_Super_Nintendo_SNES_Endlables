# Pal Super Nintendo endlables
An open source customisable endlable for Super Nintendo game cartridges

This repository aims to provide a platform for those who are looking for a nice "straight out of the box" print ready set of PAL Super nintendo end lables. Aswell as those looking to completely customise their end lable to their own style.  


# Download links

The print download links contain a zip file which includes:
* A print-ready PDF file with all the games currently supported by the chosen customisation.
* A folder containing all individual lables as PNGs. These can be used to print out lables for just the games you want or have.

> [!IMPORTANT] 
> The zip files that can be downloaded do not yet contain a PDF file. It's only exported Images for now

For a list of all current included games for each link, see the [Supported Games](#supported-games) section.

## All black endlables (print Download)

> Below is the black lable for Donkey Kong country, to provide a visual example. This lable is, ofcourse, also part of this package.
![Black lable example, Donkey Kong Country](/README_Assets/Lables/Pal_Black_Endlable_Donkey_Kong_Country.png)

The black lables contain:
* A black background.
* The Logo of the games the lables are meant for.

Download link for the all-black lables: _**[Download Files](/README_Assets/Downloadable_Files/Black_Lables_PAL_SNES.zip)**_ (Print-ready)


## Basic Endlables (print Download)

> Below is the Basic lable for Tetris Attack, to provide a visual example. This lable is, ofcourse, also part of this package.
![Basic lable example, Tetris Attack](/README_Assets/Lables/Pal_Basic_Endlable_Tetris_Attack.png)

The Basic lables contain:
* A black background.
* The Logo of the games the lables are meant for.
* The european Super nintendo Logo.
* The word "PAL" written vertically on the right side of the lable.
* A color code based on the publisher or how many copies were sold similar to the NTSC endlables.

Download link for the Basic lables: _**[Download Files](/README_Assets/Downloadable_Files/Basic_Lables_PAL_SNES.zip)**_ (Print-ready)  

## special background endlables (print Download)

> Below is the Special background lable for The legend of Zelda: A link to the past, to provide a visual example. This lable is, ofcourse, also part of this package.
![special background lable example, The legend of Zelda: A link to the past](/README_Assets/Lables/Pal_Special_Background_Endlable_Link_To_The_Past.png)

The Special background lables contain:
* A colored or image game background.
* The Logo of the games the lables are meant for.
* The european Super nintendo Logo.
* The word "PAL" written vertically on the right side of the lable.
* A color code based on the publisher or how many copies were sold similar to the NTSC endlables.
* A black background behind the Super nintendo logo, color coded strip and, the word "PAL"

Download link for the Special-background lables: _**[Download Files](/README_Assets/Downloadable_Files/Special_Background_Lables_PAL_SNES.zip)**_  (Print-ready)


## Lable Customisation file (.XCF Download)

the download link for lable customisation contains:
* The .XCF file which has all customisable options along with centered logos for the listed games.
* A folder containing all individual logos as PNGs.

Download link for lable customisation: _**[Download Files](/README_Assets/Downloadable_Files/PAL_SNES_Lable_Customisation.zip)**_ (.XCF) 
# customise lable

If you own a game that is not on this list, or, you prefer some features to be shown while some others are hidden. You might have to add a game logo manually or edit the game lable template a little bit. This section aims to show how this works.
## prerequisites

In order to follow this tutorial editing software capable of editting .XCF files needs to be installed on your Desktop or laptop. for this tutorial, the software used is GIMP. 

## downloading the .XCF file
In order to download the .XCF file, all you have to do is follow [this link](#lable-customisation-file-xcf-download) to download the file, along with a folder containing all game logos, directly.  

## adding Game logos

Assuming you have found an image of the logo from the game you'd like to add. the process is relatively straight forward. Drag the image into the software and make sure the the image is in the Game logo layer group.

![Importing image gif](/README_Assets/Step-by-step/GIF/Adding_PNG_To_Game_Logo_List.gif)

It is possible you might want to resize the image if it is too large to fit into the lable. If this is the case, select the Scale or Resize tool and select the image, click the corner of the image and resize until is (somewhat) fits into the lable. Adjust as needed.
![Resizing image gif](/README_Assets/Step-by-step/GIF/Resising_Game_Logo_To_Fit_Lable.gif)

## switching out game lables

If you want to work on a specific game lable or export the current customisation to PNG you can switch out the current Logo for a different one relatively simply. Make sure the Game_Logos layer group is unfolded. After that, all that needs to happen is to hide the layer containing the current logo, and show the layer containing the game logo you want to work on.

![Switching image gif](/README_Assets/Step-by-step/GIF/Showing_different_Game_Lables.gif)

## Selecting Special Backgrounds
If you want to switch out the background for a lable. Make sure the Game_Backgrounds layer group is unfolded. Next, hide all selected layers until the centre of the the lable is blank. Then, show the background you want to select for your lable. 

![Select background gif](/README_Assets/Step-by-step/GIF/Selecting_Special_Background.gif)

## Selecting different color codes
As some might be aware, the NTSC Super Nintendo cartridges contain a color coded stripe near the top of the lable to indicate wether it was made by Nintendo (Red) or a Third Party (Purple), Some Cartridges even have a Gold colored stripe. This indicates the game is "Players Choice" (Gold) which means the game sold over 1 million Copies.  

This feature can be shown or hidden depending on your preference. To do this, make sure the USA_SNES_Color_Code layer group is unfolded. Hide the colors that you don't want to display, and select the color you do want to display. If you do not wish to display any color, hide all colors or hide the entire Layer group.  
When customising games it might be usefull to have a look at [Publisher Color Codes](#publisher-color-codes) 

![select color gif](/README_Assets/Step-by-step/GIF/Selecting_Different_Color_Codes.gif)

## Selecting different Templay overlay
With focus being modularity with this project, A couple of layers were made to mix-and-match different parts of the lable overlay to your own preference.  
To do this, make sure the Lable_Design layer group is unfolded. Hide the features that you don't want to display, and select the features you do want to display. If you do not wish to display any of the available features, hide all features or hide the entire Layer group.

![select template gif](/README_Assets/Step-by-step/GIF/Selecting_Different_Template_Overlay.gif)

## Exporting a custom lable to PNG
in order to export a custom lable to PNG, Go to "file" in the top left corner of the screen, and select "Export As...". Next, select the location you want the lable to be saved to, enter a name for the file, and press "Export". A screen wil pop up, once again, press the option "Export". the lable should now be exported as a PNG file in the chosen folder.

![exporting image gif](/README_Assets/Step-by-step/GIF/Exporting_Final_Lables_To_PNG.gif)

# Supported Games

## games for special background end-lables (print Download)
the games that are included in the print download for the [Special background Lables](#special-background-endlables-print-download), in alphabetical order, are:

1. Donkey Kong Country
2. Link to the Past
3. Megaman X
4. Super Mario World

## games for lable Customisation file
The games that currently have a logo and thus, are [supported for customisation](#lable-customisation-file-xcf-download), in alphabettical order, are:
1. Act Raiser (3P)
2. Act Raiser 2 (3P)
3. Aladdin (3P)
4. Donkey Kong Country (PC/NIN)
5. Flashback (3P)
6. F-Zero (PC)
7. Killer Instinct (NIN)
8. Legend Of Zelfda: A Link To The Past (PC/NIN)
9. Mega Man X (3P)
10. Pac-Attack (3P)
11. Secret Of Evermore (3P)
12. Secret Of Mana (3P)
13. Star Trek Deep Space Nine: Crossroads Of Time (3P)
14. Starwing (NIN)
15. Streetfighter 2 (3P)
16. Super Mario World (PC/NIN)
17. Terranigma (3P)
18. Tetris Attack (NIN)

> [!NOTE]
> All of these games are included in the print download for: _**[All-black endlables](#all-black-endlables-print-download)**_ and _**[Basic endlables](#basic-endlables-print-download)**_. because of this these **do not** have their own list in this section

# Publisher Color Codes
like discussed in [Selecting different color codes](#selecting-different-color-codes) nintendo added a Color coded strip to the endlable in the USA-NTSC territory. This section lists the games which are included in the current version of the project (Version 1.1.0) based on their color code. Keep in mind that all Player's choice games have both a publisher and playe's choice version of their lables. this means that these games are listed in both of their respective catagories. 


## Nintendo Published (Red)
- Donkey Kong Country
- F-Zero
- Killer Instinct
- Legend Of Zelda: A Link To The Past
- Starwing
- Super Mario World
- Tetris Attack

## Third party Published (Purple)
- Act Raiser
- Act Raiser 2
- Aladdin
- Flashback
- Mega Man X
- Pac-Attack
- Secret Of Evermore
- Secret Of Mana
- Star Trek Deep Space Nine: Crossroads Of Time
- Streetfighter 2
- Terranigma

## Players Choice (Gold/Yellow)
- Donkey Kong Country
- F-Zero
- Super Mario World
- The Legend of Zelda: A Link to the Past



# Roadmap

## checklist
- [ ] Expand supported games: add remainding games from personal library. (See [Planned Supported Games](#planned-supported-games))
- [ ] Expand supported games: add all player's choice games (See [Planned Supported Games (player's choice)](#players-choice))
- [ ] Increase ease of customisation: add Publisher color-code indication to all games mentioned in Readme
- [ ] Improve Download links: Zipped Files with print ready PDF's (for now only exported lables are available)
- [ ] expand tutorial: using word to create custom print sheet
- [ ] setup a "Buy me a coffee link" for if people want to support the project :)

## Planned supported games

### Personal Game Library
- [ ] Chaos Enginge (3P)
- [ ] Disney's The Lion King (3P)   
- [ ] Dragon's Lair (3P) 
- [ ] Earthworm Jim (3P) 
- [ ] Gods (3P)
- [ ] Illusion of Time (NIN)
- [ ] Jurassic Park (3P)
- [ ] Jurassic Park Part 2: The Chaos Continues (3P)  
- [ ] Lord Of the Rings (3P)
- [ ] Mystic Quest Legend (3P)
- [ ] Run Saber (3P)
- [ ] Super Castlevania IV (3P)  
- [ ] Super NES Nintendo Scope 6 (NIN)  

### Player's choice
- [X] Donkey Kong Country
- [ ] Donkey Kong Country 2: Diddy's Kong Quest
- [ ] Donkey Kong Country 3: Dixie Kong's Double Trouble!
- [X] F-Zero
- [ ] Mario Paint
- [ ] SimCity
- [ ] Super Bomberman 2
- [ ] Super Mario All-Stars
- [ ] Super Mario Kart
- [X] Super Mario World
- [ ] Super Mario World 2: Yoshi's Island
- [ ] Super Metroid
- [ ] Super Star Wars
- [ ] Super Street Fighter II: The New Challengers
- [ ] Tetris & Dr. Mario
- [ ] Tetris 2
- [X] The Legend of Zelda: A Link to the Past