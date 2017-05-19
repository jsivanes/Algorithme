# COREWAR

Le projet Corewar consiste a créer une arène virtuelle et un programme assembleur.
	-ASM (Assembleur) : recupere un programme (dit champion) codé dans un langage assembleur simpliste et le compile en bytecode.
	-VM (Virtual Machine) : Créer une arène virtuelle et y fait affronter des programmes codés dans un langage simpliste.

## Installing & Running

Create the programme with :
'''
cd corewar
make
'''

Run ASM:
'''
./asm [-v] <file.s>
'''

Run VM:
'''
./corewar [-option (NUMBER)] <champion1.cor> <...>
	-a: Prints output from "aff" (Default is to hide it)
	-d N: Dumps memory after N cycles then exits
	-s N: Runs N cycles, dumps memory, pauses, then repeats
	-n N: Fix number of player
	-v: Show verbose mode
	-h: Hide live message
'''