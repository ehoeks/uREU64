# uREU64
**micro** (controller) based **R**AM **E**xpansion **U**nit replacement for C**64** / C128

The goal of this project is to create (the hardware and firmware) for a open source REU replacement for the commodore 8-bit home computers (like the C64 and C128). Projects for GeoRAM replacements are allready available but REU replacements seem to be expensive (or integrated in expensive multi function hardware).

## Minimal goal
* An easy firmware upgrade method (SD / USB / C64 / ...)
* Full 1764 emulation (256 kByte REU)
* Reset button (every C64 cartridge needs one)

## Dependant on cost
* Extend to 1750 emulation (512 kByte REU)

## References
* [Commodore REU on Wikipedia](https://en.wikipedia.org/wiki/Commodore_REU)
* [RAM Expansion Unit on C64-Wiki](https://www.c64-wiki.com/wiki/REU)
* [Safely freezing the C64 on an asynchronous event](https://codebase64.org/lib/exe/fetch.php?media=base:safely_freezing_the_c64.pdf) 
## Future extensions (optional)
* Graphics DMA
  - Block copy DMA (stride, block, etc) copy screen from larger bitmap graphics
  - Blitter and/or masked overlay
* Storage
  - SD-Card Backup
* ROM Cartidge emulation
  - if possible (might be to much for the hardware and should not influence the price)
