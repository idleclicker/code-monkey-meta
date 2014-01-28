The notion of **era**, will be contained in a JSON file.

Units of SLOC Gens are (SLOC/s)
Upgrades must start with a math operator
  (+-) increase the generation rate at a constant amount
  (\*/) increase the generation rate depending on how
    many production currently using

All eras have 'worker' units that perform the task. They
can moved to do work with their cost decreasing over
eras.

## Tools ##

As one might guess coding is not without tools. This might
'create' an implicit timeline forcing people to take certain
paths for certain gains/losses. As of now, these will be integrated
into this ERA file.

Another question to consider, do we make upgrades cheaper
over time, more expensive or the same price?

Era 255: (Gates)
  SLOC Generators:
    NAND/NOR Gate 1 ( 10?-clicks )
  Upgrade:
    <All upgrades this era only modify your click count>
    Only 1 is possible depending on the above
      Sum of Products Supporter (\*0.8 for NAND gate prices)
        NAND Me
         Power of 1
           Oh my minterms
      Products of Sum Supporter
        NOR Me
          Power of 0
            Oh my maxterms
    Bigger breadboard ( -1 click )
      Jumpers ( -1 click )
        Jumping ( +0.2 SLOC gen )
    -1 ( -1 click ) Only on second or later playthrough
      FF ( -1 click ) Only on third or later playthrough

  Choice:

Era 0: (Pre ASM)
  SLOC Generators:
    Punchcards 1 ( 5-clicks )
  Upgrades:
    Paper feeder: (\*2)
      Better hole puncher: (\*2)
    Buff wand (+1)
      Buffier wand (+1)
        Wand of real buffs (+1)
  Choices:
    Brand of hole puncher?

Era 1: (ASM)
  SLOC Generators:
    Keyboard 2
  Upgrades:
    Mechanical keyboard: (\*2)
  Choices:
    ?

Era 2: ALGOL, Cobol, Fortran, Lisp, Log
Era 3: Basic, MUMPS
Era 4: C, Pascal, Prolog, Sh(Bash)
Era 4.5: (DSL) [Matlab, S]
Era 5: C++, LabVIEW, Mathematica, Objective-C, Perl, Scheme, VHDL/Verilog
Era 6: GML, Java, JavaScript, Lua, Haskell, R, Python, Ruby, Visual Basic
Era 7: C#, D, Flex, PowerShell
Era 8: Dart, Go, Rust
