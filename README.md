# Project in Bash

## How to run
To compile this program, use the following command
```
./procstat.sh [options] [time]
```
The option **time** is mandatory.

The options can be:
* **-p [number]** : show just x (number) processes;
* **-c "string"** : find all processes that have the string in their names;
* **-u [user_name]** : select processes through user name;
* **-s [date]** : select all processes that start after the date;
* **-e [date]** : select all processes that start before the date;
* **-m** : sort on MEM↑;
* **-t** : sort on RSS↑;
* **-d** : sort on RATER↑;
* **-w** : sort on RATEW↑;
* **-r** : reverse;
These options are facultative.

### Example
```
$./procstat.sh -m -r -c "d.*" -p 1 10
```

## Authors
* João Reis - [joaoreis16](https://github.com/joaoreis16)
* Ricardo Rodriguez - [ricardombrodriguez](https://github.com/ricardombrodriguez)



Universidade de Aveiro, 2021
