# Melody Generation - Bio-Inspired AI Project UNITN a.y. 2021/2022
# Credits to Roberto Mazzaro, Noemi Canovi, Michele Presutto and Olga Zaghen

## What is this project :question:

This project aims to use an evolutionary algorithm with user fitness evaluation to evolve melodies. The user can give a score to melodies and rithms to generate new melodies based on what they liked more in the previous batch.

## How to run :computer:

Before running we suggest to install the basic requirements that are found inside our `requirements.txt` file however you want. The code runs with `python >= 3.8`

Then you can easily run the guy like this:

``` bash
python /path_to_this_folder/main.py
```

Following this a GUI should appear with a button to listen to each melody. Each melody also has a score between 1 and 10 to be assigned by using the score buttons. When all the scores are given, use the "New Generation" button to generate new melodies. When you are satisfied, use the "End melody generation" to let the rithm of the melody evolve or to end the program. The rithm generations evolution works the same as the melody generations evolution. At the end of both melody and rithm generations, you can decide to download the melody you like the best. You will find the ".wav" file in the "download" folder.

## Credits

This repo is only a cleaned code of this initial repo https://github.com/Rmazze/Melody_Generation. All credits goes to Roberto Mazzaro, Noemi Canovi, Michele Presutto and Olga Zaghen.
