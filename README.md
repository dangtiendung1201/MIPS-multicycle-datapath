# MIPS-multicycle-datapath

MIPS multicycle datapath made in logisim evolution for the "Computers' Architecture" course @Unimib.

Datapath and FSM are taken from "Computer Organization and Design: The Hardware/Software Interface, Mips Edition", 3rd edition.

This datapath implements:

- R-Type instructions (ADD, AND, SUB, SLT)

- Load Word

- Store Word

- Jump

- Branch Equal

- Exceptions for ADD overflow and unrecognized OP code

Repository structure:

- `slides`: here you can find the presentations used for the course, giving some hints on how to use this simulator (english slides are WIP)

- `truth-tables`: here you can find the truth tables used to generate the circuits (control unit and ALU control)

- `hex-instructions`: here you can find some examples to load in the RAM to see how the datapath works

- `exercises`: here you can find  the solution to some exercises we made for the course. The aim of each exercise is to modify the datapath to implement a new instruction or exception. Thanks to @simone-fontana, he made most of the work here, I just translated his work in logisim.
