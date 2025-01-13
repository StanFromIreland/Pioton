# Píotón

Python ach as Gaeilge! — Python but in Gaelic!

A work in progress port of the Python Programming language to Gaelic!

## Example

Currently this works:

````
>>>uimhir: uim = 10
>>>uim
10
>>>boolval = Fior
>>>if boolval == True: print("Fior == True")
Fior == True
````


## Building
### Linux Build Simple

Clone the repository and then in the cloned repository run the following commands. This may take a while.

````commandline
./configure --enable-optimizations
make -j$(nproc)
````
## Translations

None - Folamh
False - Breagach
True - Fior
bytes - bearti
complex - coimpleasc
enumerate - luaigh
filter - scag
int - uim
list - liosta

## Log

* 13/01/2025
    * Created Repository. Loaded the newest cpython version (3.14.0 alpha 3). A little cleanup.
