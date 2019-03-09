Name: Karthik Gangadhara
Student ID: 1001677851
language: Python

running commands:

Interactive Mode

    python maxconnect4.py interactive [input_file] [computer-next/human-next] [depth]

    For example:

        python maxconnect4.py interactive input1.txt computer-next 7

Argument interactive specifies that the program runs in interactive mode.
Argument [input_file] specifies an input file that contains an initial board state. This way we can start the program from a non-empty board state. If the input file does not exist, the program should just create an empty board state and start again from there.
Argument [computer-first/human-first] specifies whether the computer should make the next move or the human.
Argument [depth] specifies the number of moves in advance that the computer should consider while searching for its next move. In other words, this argument specifies the depth of the search tree. Essentially, this argument will control the time takes for the computer to make a move.


One-Move Mode

python maxconnect4.py one-move [input_file] [output_file] [depth]

For example:

python maxconnect4 one-move red_next.txt green_next.txt 5