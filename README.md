# venv-linux
A short shell script to create a python virtual environment under Linux

# Usage
If you do not have virtualenv installed, you can do it with

`apt install python3-venv`

And

`python3 -m pip install --user virtualenv`

After installing it, move to the directory, where you want to
create the virtual environment and type

`. ./venv`

The path to the script should be added to the PATH environment
variable, or the script should be in the target folder to work
properly.

After completing, the virtual environment is activated and the
path to the python excutable is printed out to check success.

To stop the environment, you should type

`deactivate`

from the folder, where you set it up.

To start it again, use

`source env/bin/activate`