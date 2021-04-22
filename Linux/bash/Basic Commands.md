Conventionally, a shellscript should start with a line such as following:
`#!/bin/bash`
to indicate the script should run in the bash (or any other).

### Variable
You can define a variable as follows: `x="hello"`
and refer to it as follows: `$x"`

Conventionally, variable names are double-quotted. If you do not need to refer to variables, single quotes are good to use as the results are more predictable.

```bash
An example

#!/bin/bash
echo -n '$USER=' # -n option stops echo from breaking the line
echo "$USER"
echo "\$USER=$USER"  # this does the same thing as the first two lines

The output looks like this (assuming your username is elflord)
$USER=elflord
$USER=elflord
```

### echo
This is the equivalent of common output commands in most programming language.

`echo "greetings"`

### Read input

`read a`
