# Vocab quiz script

This script is a python terminal program acting as a digital alternative to flash cards for learning vocab words. Applications include learning definitions of english vocab words, learning foreign language words, learning certain programming commands, ... anything whereby one wishes to learn one-to-one relationships between columns of data by heart.

Simply run the program by navigating to the folder with the terminal and execute:
python vocab_quiz.py

For the script to work, you need to have python and the pandas package installed.

The instructions for working with the program are explained in the terminal. For the program to work, an excel or csv file must be supplied, the structure of which is quite free, but it must have three columns. The first two serve as the to be tested material: words, definitions, etc. The last column serves as a filtering or category column. For example, if one only wants to test verbs. An example excel file is supplied in this repo. Starting the program will search the directory it is in for xlsx, xls or csv files. If none is supplied in the current directory, you can point the program to a word table using the command [i].

Defining how the program will test you is set up with the settings. You can set it up so it asks only words from the first column, only from the second column, or both. You can filter by category also through the settings.

At present, the program does not check the answers you provide against the answer in the table, as I had no need for this. You hack this together pretty quickly if you want this by editing the vocab_loop method.

Happy vocab learning.
