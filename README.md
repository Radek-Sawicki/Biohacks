Noisereducer now has proper data control and is finished! It gracefully handles:
empty file: error all columns removed

empty sequences: error all columns removed

all columns removed: error all columns removed

extra newlines between sequence lines or between sequence and name: nothing bad happens

no arrow before a name: error corrupt data

sequences containing anything else than aminoacid letters or hyphen: error corrupt data

