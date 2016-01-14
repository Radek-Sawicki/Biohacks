This one works good with error checking for equal lenght of sequences in one MSA.
However, it seems like a bad idea to store sequences in a dictionary IF one is to
let the program iterate over all files (all MSA) by itself. then the different MSAs
get mixed up. But it is ok if one will make a shellscript to iterate over the files
calling the script anew each time.

This script can print(identify) all the columns in a MSA.
