# gfx-otype

GfxOType for [polpo](https://github.com/polpo-system/polpo): TrueType and OpenType fonts (the package
otype) as fonts of Gfx (the package gfx). `TTF = GfxOType.Install` in the section FontFormats of
Oberon.Text makes Gfx look for .TTF files.

```
portia.Install gfx-otype
```

## What is here

    src/GfxOType.Mod         the font class
    test/GfxOTypeTest.Mod

The source comes from ETH Linux Oberon (OLR, 2017-06-18), converted from an Oberon text to plain
text; the first commit has it unchanged. It compiles unchanged with all five of polpo's compilers
(x86, ARM, ARMv7, RISC-V, MIPS).

## Tests

    GfxOTypeTest.Run      1 check: the module loaded; it needs the desktop's display

The license is GPL-3 (`LICENSE`); the code comes from ETH Oberon, whose license (`LICENSE.ETH`)
asks to keep its copyright notice and conditions, which `LICENSE.ETH` does.
