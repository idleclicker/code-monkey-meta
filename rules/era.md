The notion of **era**, will be contained in a JSON file.

Units of SLOC Gens are (SLOC/s)
Upgrades must start with a math operator
  (+-) increase the generation rate at a constant amount
  (\*/) increase the generation rate depending on how
    many production currently using

All eras have 'worker' units that perform the task. They
can moved to do work with their cost decreasing over
eras. As with a timeline, we might add in bonus eras that provide certain
benefits to the rest of game and conditions for getting it.

Another option to consider is to not have workers and be a solo worker.
We might have to consider the pros and cons of it.

(The timed era transitions might not be implemented early since its not
 typical of a clicker game to have that.)
The act of transition to the next era, can vary. Currently, we might
have the player unlock it but one option to consider is a timed game,
where eras will auto advance and players compete for a high score,
in a fixed amount of time.

## Tools ##

As one might guess coding is not without tools. This might
'create' an implicit timeline forcing people to take certain
paths for certain gains/losses. As of now, these will be integrated
into this ERA file.

These will include
  * equipment upgrades
  * new application/platforms used
  * potentially new coding techniques (this might be moved out later)
  * new community/forums

Another question to consider, do we make tools and their upgrades cheaper
over time, more expensive or the same price?

##


## Alternative Costs ##

Flesh out a bit in the issues for the Github repo but, will we have
alternative costs like people? This will allow for alternative units
like ***projects*** completed, ***files/projects*** created and the like?

Perhaps these will be used in upgrades and the like?

## SLOC Containers ##

This might make some sense in the earlier eras but given the fact that
processing power and memory/space was very small, there might have
to be a cost in holding SLOC and a build time to say build the project,
via collecting the SLOCs and what not. After all does anyone have zip 100s?

Related to this might be security if the SLOC are used to build new products.

No worker helpers available.
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
    You can only pick NANDs or NORs.
  Perhaps around ~3000 clicks to get to next era? IC era?

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
