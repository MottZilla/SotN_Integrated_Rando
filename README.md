# SotN_Integrated_Rando

Video Tutorial: https://youtu.be/dWpGx8LZtOs

# Castlevania Symphony of the Night - Integrated Randomizer

1. Getting Started (Patching)

Download the latest version from Releases on the Github page. Apply the PPF patch to the Track 1 BIN file using your PPF patcher of choice. You could use https://ppf.sotn.io or https://www.romhacking.net/patch/ to apply. Your original unmodified Track 1 BIN should have the checksum values:
MD5: acbb3a2e4a8f865f363dc06df147afa2
CRC32: 05BE47B2

Once your file is patched if you want to play Maria mode (optional, not required) you will need to use the tool located here: https://github.com/MottZilla/MariaGfxImport

Use the buttons and follow the prompts. You will first select your PSP Dracula X Chronicles ISO and then click the Import GFX and Export PSX Maria BIN button. Once you have the Maria.BIN file you should see the buttons to select your PSX Track 1 BIN. Select the Track 1 BIN you applied the PPF patch to and then check the checkbox for Import for Integrated Console Rando. Click Import Maria.BIN. It is advised to put all the files in the same folder while doing these steps to make it easier.

2. Loading the Randomizer (Platforms)

The randomizer is compatible with original PS1 consoles, PS2 consoles, and emulators. I personally tested it on the PS1 SCPH-7501, PS2 SCPH-50001, the MiSTer PSX Core, and BizHawk's Nymashock PSX Core. If you plan to burn a CD-R for play on a real system you should do the steps to install the MARIA.BIN first as you can't do that once you've burned a disc. Before burning the disc you should test on an emulator to know it's working. If you installed Maria you should test her mode on emulator before burning! You also will need to have a method of booting the CD-R as unmodified consoles will not start it normally. 

3. Console Boot Methods

For the original Playstation you could boot the randomizer with a Swap Trick, Stealth Unlocker, TonyHax, or modchip. Be aware that Unirom conflicts with the rando and many presets don't work if you boot using Unirom. One of the most accessible methods would be to use TonyHax from a memory card like the sd2psx. Note that swap tricks can lead to worse disc reading.

For Playstation 2 if you have a SCPH-50000 or higher you could look into Mechapwn to enable your system to boot CD-Rs and Imports. You could also look into Swap Trick methods. Finally there are modchips. It might also be possible to run it with OPL or Popstarter.

For Playstation 3, I imagine if your system is modded it would work, untested though.

4. What can the Randomizer do?

The randomizer has Presets which are modes that can change small to large aspects of how the game is played. It also has options which can be toggled for any Preset unless it's incompatible. The location of relics, items dropped from enemies, items found in stages, items found in the shop, items found in candles can all be randomized. There are currently over 20 presets to choose from and many options to toggle. Descriptions are displayed in the menu. Many presets change the gameplay experience into something new!

5. What is the Seed?

When you start a randomizer playthru you select the Preset and get a random Seed number unless you choose to enter a specific number. The seed number determines how everything gets randomized. If you play through in one session to the end you don't need to remember your Seed number and preset. But if you plan to save and continue later see saving the game below!

6. Saving the Game

If you plan to save your game and resume playing a Seed later you need to note the Preset chosen, Seed #, and any option changes from the default settings. You can see the Preset and Seed # in the Pause screen while playing. When you reload the game after saving you will need to select the same Preset and Seed # and should select the same options if you changed any from the preset's default options. If you do this you should have no trouble resuming your randomizer seed later!

7. Helpful Tips

Included are the MapTracker and RelicTracker features. If you access the Map with the Select button you will see small squares showing you which locations are "Relic Checks". These are locations that could have one of the relics. Also while playing if you hold the L2 button you can use the RelicTracker which is an overlay showing you while Relics you have obtained so far. 

8. Links

Integrated Rando Github
https://github.com/MottZilla/SotN_Integrated_Rando

Maria Tool to Generate and Import MARIA.BIN
https://github.com/MottZilla/MariaGfxImport

Separate Randomizer Project in Javascript
https://sotn.io

The Long Library Discord
https://discord.com/invite/dzbKhQDjrs

---

Thanks to the following for helping beta test!

Calvitium,
Crazy4Blades,
DerDrach,
Doozy,
Dr4gonBlitz,
eldri7ch,
Gods666thChild,
JupiterClimb,
Mcnair,
MT_Fun,
olfaithfulrage,
RJarcade,
Sestren,
SirEJ,
Sonic Dreamcaster,
ToiletPain,


