OCR Correction Program
Coded by Ben Phung, Ed Ruiz, and Ned Watson

This program uses matrix algorithms as well as the Levenshtein distance to calculate
the best replacement of a misspelled word by factoring in frequency and proximity to 
a word in a dictionary tree.


Instructions:
1) Unzip loudhum.zip. Download the loudhum directory. 
2) Unzip CorrectionProgram.zip
2) Run the program project.rkt. You can change the input files by removing or adding files in the
   corpus method in project.rkt (first method).
3) If there are errors, run all the dictionary racket programs first to ensure that
   the dictionaries have been built.


Folder descriptions:
masc_500k_newswires - test files using Wall Street Journal and New York Times articles.
SandB - another folder for test files
compiled - folder for errortracing
scowl-2018.04.17 - folder for other languages and variants. See the read file for more details.


Special thanks to:
- Yutaro Yoshii and Jung-Won Lee for a tree searching idea. This helped us realize to build a
  dictionary word tree for efficiency.


Credits:
- loudhum directory is from the Grinnell Computer Science department.
Link to download: https://github.com/grinnell-cs/loudhum
- other credits for specific folders are given in files inside.
- SandB: another library taken from Grinnell CS Department.
- each wsj_XXXX.txt file from WSJ and NYTnewswireX.txt from NY Times.
