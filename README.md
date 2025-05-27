# Reverse Engineering 4 Fun & Profit
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![RE4F & Profit](https://img.shields.io/badge/discord-blue.svg?logo=discord&logoColor=f5f5f5)](https://discord.gg/2GZBkXnrjQ) (**Arabic Discord Server**)
#### Reverse Engineering - Tools and Techniques

- What & Why
	- What is Reverse Engineering?
    - Why Reverse Engineer?
    - Types of Reverse Engineering
    - Tools used in Reverse Engineering

* Introduction to Reverse Engineering
	* CPU Architecture
		* x86 vs x64 Architecture
		* Registers and their functions
	* Number Systems
		* Hex
		* Dec
		* Bin

* Introduction Windows Memory Management
	* Physical Memory
	* Virtual Memory
	* Memory Addressing

* Introduction to Assembly
	* What is Assembly Language?
	* Assembly Language vs High Level Language
	* Assembly Language Syntax (Assemblers) & IDE
		* Linker: Golink / GCC 
		* NASM / MASM / FASM
	* Basic Instructions 
		* NASM Syntax [NASM Syntax](Into2Asm/NASM%20Syntax.md) / MASM Syntax [MASM Syntax](Into2Asm/MASM%20Syntax.md)
		* NOP, MOV, ADD, SUB, INC, DEC, MUL, IMUL, DIV, IDIV (FLAGS) [Basic Instructions](Into2Asm/Basic%20Instructions.md)
		* AND, OR, XOR, NOT, SHL, SHR, ROL, ROR [Bitwise Instructions](Into2Asm/Bitwise%20Instructions.md)
		* JMP, CMP, TEST & (JZ = JE, JNZ = JNE), JL, JLE, JG, JGE etc.. [Conditional Logic](Into2Asm/Conditional%20Logic.md)
		* LEA & Strings Related Instructions (RSI, RDI, RAX) [LEA - String Instructions](Into2Asm/LEA%20-%20String%20Instructions.md)
		* PUSH, POP, CALL, RET & Stack / Functions Prolog - Epilog (Enter, Leave) | Params  -> Call Convention [Functions related Instructions](Into2Asm/Functions%20related%20Instructions.md)
			* PUSHAD, POPAD (only in 32bit)
		* Call an external API [Call windows API](Into2Asm/Call%20windows%20API.md)

* Introduction to Debuggers (Basics)
	* x64dbg Walkthrough
	* IDA Free Walkthrough
	* WinDbg Walkthrough
	* OllyDbg Walkthrough

* Windows Internals [Win Internals](Windows%20Internals/Win%20Internals.md)

* Overview of Portable executable 
	* [PE Info](PE%20Files/PE%20Info.md)
	* [PE Loader](PE%20Files/PE%20Loader.md) Workflow

- Analysis 
	- Static Analysis [Static](Analysis/Static.md)
	- Dynamic Analysis [Dynamic](Analysis/Dynamic.md)

- Anti Analysis Techniques
	- [Packing](Anti%20Analysis/Packing.md)
	- [Anti Debugging](Anti%20Analysis/Anti%20Debugging.md)


Use https://obsidian.md to open this repo.