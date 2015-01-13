MASCHE
======
![MASCHE image (Javier Mascherano)](http://i.imgur.com/V3EMjswm.jpg)
**MIG Memory Forensic library**

**MASCHE** stands for **Memory Analysis Suite for Checking the Harmony of Endpoints**. It is being developed as a project for the *Mozilla Winter of Security program*.

It works on **Linux**, **Mac OS** and **Windows**.

These are the current features:

 * listlibs: Searches for processes that have loaded a certain library.
 * pgrep: Has the same functionallity as pgrep on linux.
 * memaccess/memsearch: Allows access and search into a given process memory.

You can find examples under the examples folder.

## Compiling

### Linux
You need glibc for 64 and 32 bits installed. On Fedora, the packages are:
* glibc-devel.i686
* glibc-devel.x86_64
* glibc-headers.i686
* glibc-headers.x86_64
* glibc.i686
* glibc.x86_64
 
### Windows

In order to compile and run masche in windows you will need a gcc compiler. You can use mingw if you are running a 32 bits version of Windows or mingw-64 if you are running a 64 bits one.
