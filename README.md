Treedistmetric.py is almost finished! Perhaps just another line about rootmean-square 
of the distances deviation from zero would be needed.

The program might workusing the command ">treedistmetric.py *.tree" in Unix, the script is designed for it.

Noisereducer now has proper data control and is finished! It gracefully handles:

empty file: error all columns removed

empty sequences: error all columns removed

all columns removed: error all columns removed

extra newlines between sequence lines or between sequence and name: nothing bad happens

no arrow before a name: error corrupt data

sequences containing anything else than aminoacid letters or hyphen: error corrupt data


