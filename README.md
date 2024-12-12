Requires python to be installed and in PATH. Tested with python 3.13, but should work with most versions

To Use : Place the .py file in the same directory as the VHDL file you wish to make a template for. Open a terminal instance in this directory, and call the script, alongside the name of the file. 

E.g python3 vhdl_tb_generator test.vhd    , where test.vhd contains an entity FullAdder

This will result in a testbench being created with the name FullAdder_tb.vhd, and saved in the same directory as the source file

Multiple vhdl files can be passed as arguments at once, and a testbench file will be generated for each of them.


If you want to make functional improvements to the script please raise an issue or a pull request. If you want to tweak it for your own use (e.g a different template or additional packages) please clone and make the changes locally, or branch. 
