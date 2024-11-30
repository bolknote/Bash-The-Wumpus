# Bash The Wumpus
#### This is a remake of the classic 1970s text adventure, but on a file system. Written in bash.

<img width="454" alt="screenshot" src="https://github.com/user-attachments/assets/6e057f46-79d8-4bc5-a9be-7668f1d0639b">

The screenshot shows a situation where I shot into the wrong room, missing the one where the Wumpus was sleeping. It woke up and got me.

When the game starts, it will display instructions taken from the original game. All messages are also taken from the original game. The player interacts with the game through commands entered after the bash prompt. Here are the commands needed for the game:

- `ls` - to see which rooms the tunnels lead to
- `cd` - go to a room with a given number
- `rm` - shoot through tunnels (separated by a space)
- `exit` - leave the game

NB: the `rm` command does not behave as it normally does in bash. Its parameters specify the room numbers the arrow, fired by this command, should pass through.

PS: the game resists cheating attempts, but if you're a skilled hacker, you can easily bypass these measures.
