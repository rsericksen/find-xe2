# find-xe2
A lightweight script designed to locate hidden characters in a python script that cause interpreter errors.

This script will search {FILENAME}.py for any instances of the invible character "\xe2" where {FILENAME} is the name of your python script. The script will output the lines, line numbers, and locations within the text where these characters appear so they can be deleted manually by the user.
