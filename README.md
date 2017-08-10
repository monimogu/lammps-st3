# Snippets for quick LAMMPS input file

Put these files in you _User_ folder in ST3 for file highlighting and auto-completion of lammps input files. _User_ folder can be accesed by going to menu: _Prefernces > Browse Packages_. Usually the bottom-most folder will be _User_.

All files with extension *.in or *.lammps should show syntax highlighting now.

Currently there are 3 kinds of snippets: 

1. For initialization (atom type, periodic boundary etc). It contains all settings most commonly used by _me_ you can edit it as per your wish. To use it write **init** followed by <kbd>Tab</kbd> to complete it.
2. For import velocity command in create model. type **velocity** followed by <kbd>Tab</kbd> to complete it. now use <kbd>Tab</kbd> to cycle through all the fields you want to edit or fill.
3. Dump Files: Triggered by **dump** + <kbd>dump</kbd>. It will create a dump command to output your run states in style of atom by atom.




As it should be obvious if anything goes wrong with your simulations or computers or anything else, you are only responsible for that.
