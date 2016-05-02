SYNOPSIS:
	This project is an attempt to port the Uniform Driver Interface to
	SEL4.

MOTIVATION:
	I have an interest in seeing how a fully asynchronous driver API
	would function on top of SEL4, and also believe that SEL4 is more
	mature than my own kernel, Zambesii.

	If the benefits of UDI are to be explored, they would best be
	explored in SEL4, and I can later finish porting UDI to Zambesii.

	The project will also serve to orient me both to using CAmkES and
	to writing drivers for SEL4. It should also be an interesting exercise
	to get C++ applications running under SEL4, though I may choose to
	use pure C to get the formal verification angle as a side-benefit.

ROADMAP:
	1. UDIProps parser.
	2. Basic address space setup for drivers.
	3. Driver metadata parsing and collation.
	4. Device->driver search and matching.
	5. Creating a basic driver instance.
	6. IPC.
	7. UDI Core syscalls.

