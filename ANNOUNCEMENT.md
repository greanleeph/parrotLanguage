<h2>Parrot compiler now runs on both Linux and Windows platforms via GCC!</h2>

* This version of the compiler now uses C as the intermediary language rather than Assembly so both Linux and Windows platforms can simply use GCC to compile the intermediary language to machine code.

* The GCC compilation phase is also embedded within the Parrot compiler, so instead of taking 3 separate steps to compile the  `prrt` code into machine code, it now only takes one step.

* Bug with cell referencing fixed!!! (and other bugs)
  
* Added some new demo code for Parrot

* Removed 'spin' loop because I don't like it...
