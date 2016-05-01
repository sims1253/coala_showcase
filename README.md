# This repository is used to showcase what coala can do on conferences.

##Usage
- coala -A
This shows all the bears

- coala -l java
This shows all the bears that are compatible with java


- open .coafile with an editor of your choice. 
Point out how there can be different categories and different bears in the conferences. Files can be choosen acordingly. Parameters can be set and auto patching for bears can be enabled. 


- coala -s
This runs all sections in the .coafile. You are asked for a parameter that is needed and not specified in the .coafile. Then the code doublication in the .java files is shown. You can print additional info, open in editor or skip.
Then the pep8 bear shows an error. You can show the diff and apply the patch automaticaly.
Running this again will not ask for the use_spaces parameter again as it is saved in the .coafile due to the -s flag.


- coala-ci
This runs the ci version that does not require user interaction. This will just show an error because the use_spaces parameter is not supplied.

- You can open up a simple bear, like LineCountBear, to showcase how a bear works and how easy it is to write a new one.

- You can open up the VHDLLintBear to showcase how easy it is to wrap an existing linter. It was written in around 15 minutes at the linuxwochen conference.