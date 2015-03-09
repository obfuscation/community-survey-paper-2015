Welcome to the Obfuscation Research Community initiative to write a summary
article about the state of network obfuscation.

More information about the initiative is available at 
https://docs.google.com/document/d/1IRXlfsQC4xwlQECosRfkNupU3DHN2WWosrjvgHfWhLs/

And an associated Google Group is at:
https://groups.google.com/forum/#!forum/censor-circ-paper


***Files***

main.tex :   
this is the main latex file, which includes all others

macros.tex: 
put any global macros here. Try to use only global macros, as we don't want to
search through all tex files for someone's macros in case of a conflict

packages.tex:
put any package additions and configuration options here

The other tex files are for individual sections. If you want to add a new tex
file for some material, feel free. 


***Token management***

By token I mean being able to make changes to a portion of the paper.  This
directory contains the work-in-progress Latex writeup. Currently everyone given
access to the repo is encouraged to edit any portion of the paper, but to avoid
stepping on each others toes let's remember to coordinate tokens via
https://docs.google.com/spreadsheets/d/1ftqRzdd97_HcElMSkfTZ2QL3yThp31IXQUpPtnQUCOY/edit?pli=1#gid=403066943

The protocol is to please add your name to the list and indicate what sections
you are working on. Please always update your local copy before starting
changes. You can put in Latex file names to lock the entire file, or just
indicate at the granularity of  section headers. (Please indicate the full
(sub)section  title as well as number in case section numbering changes.)

In case of a conflict, please figure out who made edits (emails are in the
second sheet of the Google spreadsheet) and reach out to them to
resolve the conflict (assuming a simple merge doesn't work). 


***Authnotes***

You'll see in macros.tex the macro \tcrnote. Feel free to append to this list
your own macros to add in-line comments. You can turn off authnotes by setting
the flag in macros.tex to 0. 



