# Producer-Consumer-Problem
A message based producer consumer program for linux with four processes. The reader process will read an input file, one line at a time. Reader will take the each line of the input and pass it to process Process1.  Process1 will scan the line and replace each blank character with an ("*") character. It will then passs the line to process Process2. Process2 will scan the line and convert all lower case letters to upper case, it will then pass the line to process WRITER. Writer will write the line to an output file.