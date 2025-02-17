# GACSA-EZ48
**What this repository is for**: This is a Replica and preservation site for the GACSA EZ-48 Home Computer from 1981.

# History

A couple years ago, I found a video on latin american home computers from 1985(https://www.youtube.com/watch?v=YCAkC38AB9X) in it they covered many locally made computer designs and manufacturing of foreign designs in the region, but the ones who caught my attention the most were the mexican Oscar Toledo's OTEK I machine and the machines produced by the company Grupo Atlacatl Comercial in El Salvador, I really liked the ideas in both, but sadly, the first one is totally undocumented, and the second is barely documented(specially since being a one person homebrew machine), and most of the documentation is lost to time or in terrible condition, so the effort to recover as much as possible from it would be Titanical, but perfectly possible.

# More on the machine and its origin
GACSA produced several home computers from the late 70s to its demise and bankruptcy in early 90s, probably the one which is less lost to time was the GACSA EZ-48, with the original model releasing in 1979 and re-releasing an improved EZ-48 II in 1981(which included revised versions of their Audio and Video ICs), it's notable for only using either locally sourced parts from Texas Instruments(Video, Audio, Logic, RAM, etc) with the exception of the CPU and peripheral adapters(being these sourced from Rockwell in Mexico), it was a comercial success selling probably around 100,000 units until 1992.

# Specifications
* Rockwell 6502A at either 1.79Mhz (original EZ-48) or 2.148Mhz(later EZ-48 II units)
* TMS9918A Video Display Processor with 16K of Video Memory and Genlock capability
* SN76489 Audio IC with 4 channels
* 48K of Dynamic RAM
* Microsoft BASIC in 3 4K ROMs(Apple Compatible) 
* 4 expansion slots (There were many expansions avaible, 80 columns cards, floppy interfaces, CPU expansions, etc)
* 1 or 2 cartridge slots
* 64 keys 8 by 8 ASCII keyboard with AVX(ALPS compatible) switches, with Ñ and ₡ (colon) symbols
* Cassete interface at 1200bps CUTS standard
* Parallel Printer port and options to fit a Serial Adapter and TMS5100 based voice generator(later units fitted them with an expansion card, it used the voice of [Willie Maldonado]([https://www.genome.gov/](https://en.wikipedia.org/wiki/Willie_Maldonado)). **Not going to be fitted, at least on V1**

# Current Status/ To-Do list

This project is in a very early stage, and should not be copied blindly in its current state, it has been re-started in order to be Kicad 8 Compatible(I started it on Kicad 6), so far, this seems to be the roadmap for the project

- [ ] Fit the ICs to be used in Kicad
- [ ] Route the connections on each IC as close as possible to schematics
- [ ] Design the mainboard
- [ ] Copy the keyboard in Kicad
- [ ] Copy the board artwork(an original board would be needed, highly unlikely to ever happen)
- [ ] Get a BASIC ROM or cartridge for the machine(there have been many cartridges circulating on downtown San Salvador e-waste shops, but all of them have been now closed, so highly unlikely)
- [ ] Print the PCBs for both the keyboard and mainboard, test them to boot 
- [ ] If the previous step fails, write a diagnostics ROM
- [ ] Re-do the board based on the originals (if I ever come to find one)
- [ ] Recreate the computer's case and power supply (This should be easy, the power supply was identical to the TI-99 4/A)
- [ ] Recreate the expansion boards(if ever surface)

# So... how I am going to pull this off?

That's the neat part! Probably I won't! But that's not going to stop me from trying, as the original machine took some inspirations from the Apple II and the TI 99 4/A, at least there are many starting points with that information.

# License

All Source Code and design files should be considered free software/hardware, covered under the GPLv3 License, ROM Files(if they ever surface) should be considered propietary intellectual propierty by Microsoft, Grupo Atlacatl Comercial S.A. (or anyone who own their rights, it's seems the last owner of the company was Microstrategy) and should not be used for commercial purposes.

# Thanks to

This project is an effort to preserve a significant piece of Latin American computing history. Contributions, information, and original hardware scans are highly appreciated!. I want to thank to the Kicad developers for making such a great piece of Software
