# GACSA-EZ48

**Purpose of this Repository**: This repository serves as a replica and preservation site for the GACSA EZ-48 Home Computer, originally released in 1981.

# History

Several years ago, I stumbled upon a video detailing Latin American home computers from 1985 ([Video](https://www.youtube.com/watch?v=YCAkC38AB9X)). The video covered various locally manufactured computer designs and the production of foreign designs in the region. Among these, the Mexican Oscar Toledo's OTEK I machine and the computers produced by Grupo Atlacatl Comercial in El Salvador stood out. Both designs were intriguing, but unfortunately, the OTEK I is largely undocumented, particularly since it was a one-person homebrew project. The GACSA machines, while slightly better documented, have seen much of their documentation lost or degraded over time. Despite the daunting task, recovering as much as possible from these machines is both challenging and feasible.

# More on the machine and its origin

Grupo Atlacatl Comercial (GACSA) produced several home computers from the late 1970s until its bankruptcy in the early 1990s. The GACSA EZ-48, released in 1979, and its improved version, the EZ-48 II, released in 1981, are among the most notable. The EZ-48 II featured revised versions of its Audio and Video ICs. A unique aspect of these machines was their reliance on locally sourced components from Texas Instruments (Video, Audio, Logic, RAM, etc.), with the exception of the CPU and peripheral adapters, which were sourced from Rockwell in Mexico. The EZ-48 series was a commercial success, with approximately 100,000 units sold by 1992.

## Specifications

- **CPU**: Rockwell 6502A at 1.79 MHz (original EZ-48) or 2.148 MHz (later EZ-48 II units)
- **Video**: TMS9918A Video Display Processor with 16K of Video Memory and Genlock capability
- **Audio**: SN76489 Audio IC with 4 channels
- **RAM**: 48K of Dynamic RAM
- **ROM**: Microsoft BASIC in 3 4K ROMs (Apple Compatible)
- **Expansion**: 4 expansion slots (various expansions available, including 80-column cards, floppy interfaces, CPU expansions, etc.)
- **Cartridge Slots**: 1 or 2 cartridge slots
- **Keyboard**: 64-key 8x8 ASCII keyboard with AVX (ALPS compatible) switches, including Ñ and ₡ (colon) symbols
- **Cassette Interface**: 1200bps CUTS standard
- **Ports**: Parallel Printer port, with options for a Serial Adapter and TMS5100-based speech synthesizer (later units included these as expansion cards, using the voice of [Willie Maldonado](https://en.wikipedia.org/wiki/Willie_Maldonado)). **Note**: These add-ons voice generator will not be included in V1.


# Current Status/ To-Do list

This project is in its early stages and should not be blindly replicated in its current state. It has been restarted to ensure compatibility with KiCad 8 (originally started on KiCad 6). Below is the proposed roadmap for the project:

- [ ] Fit the ICs to be used in KiCad
- [ ] Route the connections on each IC as close as possible to the original schematics
- [ ] Design the mainboard
- [ ] Recreate the keyboard in KiCad
- [ ] Copy the board artwork (an original board would be required, which is highly unlikely)
- [ ] Obtain a BASIC ROM or cartridge for the machine (many cartridges were once available in downtown San Salvador e-waste shops, but these shops have since closed)
- [ ] Print the PCBs for both the keyboard and mainboard, and test them to ensure they boot
- [ ] If the previous step fails, write a diagnostics ROM
- [ ] Redesign the board based on the originals (if an original board is ever found)
- [ ] Recreate the computer's case and power supply (the power supply was identical to the TI-99 4/A, making this step relatively straightforward)
- [ ] Recreate the expansion boards (if they ever surface)
      
# So... how I am going to pull this off?

That's the neat part—I probably won't! But that won't stop me from trying. The original machine probably drew inspiration from the Apple II and the TI-99 4/A, providing several starting points for this project.

# License

All source code and design files are considered free software/hardware, covered under the **GPLv3 License**. ROM files (if they ever surface) should be considered proprietary intellectual property by Microsoft, Grupo Atlacatl Comercial S.A. (or any current rights holders, as it appears the last owner of the company was Microstrategy), and should not be used for commercial purposes.

## Acknowledgments

This project is an effort to preserve a significant piece of Latin American computing history. Contributions, information, and original hardware scans are highly appreciated. Special thanks to the KiCad developers for creating such a robust and versatile piece of software.
