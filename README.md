# In Class Problem Set 3

I used ComboBoxDemo.java a few years ago.  It used to compile cleanly.  Even though the code has not changed, it now  will not compile without throwing warnings.

Doing everything from a command prompt or Git Bash (no IDEs allowed), your mission is to debug the code and find out why it stopped compiling cleanly.  When you have figured it out,  note what you changed and why it stopped working in the README.md file.


**Changes to code**
Added A SerialVersionUID in order to ensure compabitability, also changed JComboBox to JComboBox<String> to get rid of the raw type and make it generic.  


**What caused it to stop working?**
The code stopped working due to java updating, which caused the raw type of JComboBox which could cause runtime errors. Also updates to the UI updates could cause errors.
