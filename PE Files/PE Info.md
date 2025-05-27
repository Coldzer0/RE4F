* PE Headers
	* Dos Header
		* e_magic / MZ Signature
		* e_lfanew / Address Of New Exe Header
	* NT Header
		* File Header
			* Machine
			* Number Of Sections [Section Info](Section%20Info.md)
			* TimeDataStamp - ( Time stomping )
			* Characteristics - EXE or DLL etc...
		* **Optional Header**
			* Data Directories 
				* Import Address Table
				* Bound Import Directory
				* Export Address Table
				* Relocation Directory 
				* Exception Directory - x64bit only
					* TEB - Exception List - x32bit only
				* TLS Directory 
				* Debug Directory
	* Section Headers
		* Name
		* RAW - Virtual Addresses 
		* How to convert from RAW 2 Virtual <>
		* Characteristics

* Understanding PE file formats 
	* [DLL](DLL.md)
	* [EXE](EXE.md)
	* [SYS](SYS.md)
	* [OCX](OCX.md)  - Com Objects


