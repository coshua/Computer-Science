Loops can be performed in several ways.

### Loop with 


### Condition

if statements take form
```bash
if [[ condition ]]
then
  do this
elif [[ condition2 ]]
then 
  do this instead
else
  do this by default
fi
```
Note that *then* is required after *if* and *elif* but not after *else*.
It must be seperated from the conditional line by either a newline or a *;*, which represents a newline to bash.
An or condition is *||* and *and* condition is *&&*.

There must be a space between the brackets and their contents.
`if [[ $a -lt $b ]]`
