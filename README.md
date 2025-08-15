# tekisuto

- The Sims 3. Steam Version.
- Text Changes for:
  - Grammar
  - Spelling
  - Punctuation
  - Word Choice
  - Redundancy
  - Wordiness
  - etc.
- Language
  - en-US (English-USA)

## Instructions

1. Download the latest version at [releases](https://github.com/VMPYRC/tekisuto/releases)
2. Extract the attached .ZIP file into your mods folder
3. Remove any .package files associated with Expansion Packs, Stuff Packs, or Items that you don't own or use
4. Play + Enjoy
5. Submit Issues & Suggestions [here](https://github.com/VMPYRC/tekisuto/issues)

## Notes

### My process

1. View the original packages (see section below) in [s3pe](https://sourceforge.net/projects/sims3tools/files/s3pe/)
2. Within s3pe, checkmark the `Tag`, fill in `stbl` in the field under `Tag`
3. Click the `Set` button
4. Checkmark `Filter active`
5. Select the `Strings_ENG_US...` file
6. Right click
7. Export
8. To package...
9. Within the popup File Explorer
   1. Choose a location (preferably an empty folder)
   2. Set a file name
   3. Open button
10. Open the newly created package file in s3pe
11. Select the STBL file, and a preview should open
12. CTRL + A - to select all in the preview
13. CTRL + C - to copy the selection
14. Open text editor
15. CTRL + V - paste the contents
16. Save as a .txt file
17. Open the newly created package file in [s3se STBL Editor](https://simlogical.com/ContentUploadsRemote/uploads/1947/)
18. Make your edits
19. Save
20. Repeat steps 10 to 16
21. Track changes with txt files and through Git. Development must be linear because of the way STBL and package files work.
22. The loop is steps 17 to 21

### Folders

- STBL
  - for package files
  - each package includes a STBL and KEY file
- TXT
  - used to track text changes because Git cannot read package files
  - mainly for humans to view

### Originals are from

- Program Files (x86)\Steam\steamapps\common\The Sims 3\
  - GameData\Shared\Packages\
    - DeltaBuild0.package
    - Base Game
  - EP#\GameData\Shared\Packages\
    - FullBuild0.package
    - All Expansion Packs (`EP_#`)
  - SP#\GameData\Shared\Packages
    - FullBuild0.package
    - All Stuff Packs (`SP_#`)
- Store Content packages
  - All Items (`Item_ABC`)

### All

```
BaseGame
EP1_WorldAdventures
EP2_Ambitions
EP3_LateNight
EP4_Generations
EP5_Pets
EP6_Showtime
EP7_Supernatural
EP8_Seasons
EP9_UniversityLife
EP10_IslandParadise
EP11_IntoTheFuture

Item_ArtisansGlassblowingAndJewelryMakingStation
Item_FitAsAFiddleViolin
Item_StiffAsABoardDanceFloor

SP1_HighEndLoft
SP2_FastLane
SP3_OutdoorLiving
SP4_TownLife
SP5_MasterSuite
SP6_SweetTreats
SP7_Diesel
SP8_70s80s90s
SP9_Movie
```
