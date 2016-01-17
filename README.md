The program seems to be done now, if writing to stdout would be enough. 
result_testdata confirms that the correct annotations get correct letters.
•	The “all columns removed” error will do for empty file and empty seq cases too.
•	Checked that extra empty lines after an MSA does not cause bugs.
•	Changed “key” variable names to distinct ones (key, key2, key3) in columnremover to avoid risk of bugs. All controls and test still worked afterwards.
•	Now columnremover prints out in fasta format to stdout!

