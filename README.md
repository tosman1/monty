# MONTY
![alt text](https://pbs.twimg.com/media/CFYYWy6UEAE9Ow-.png)

## Description

Monty 0.98 is a scripting language that is first compiled into Monty byte codes (Just like Python). It relies on a unique stack, with specific instructions to manipulate it. The goal of this project is to create an interpreter for Monty ByteCodes files.

***

## Installation

1. Clone the repository:
```console
https://github.com/tosman1/monty.git
```

## Usage
1. Enter at directory
```console
cd monty
```

2. Compile:
```console
gcc -Wall -Werror -Wextra -pedantic -std=c89 *.c -o monty
```

3. Execute:
```console
./monty file.m
//The file contains the bytcode instructions for example
cat -e 000.m
push 0$
push 1$
push 2$
  push 3$
                   pall    $
push 4$
    push 5    $
      push    6        $
pall$
```

## Functions

The functions used are:

|Name | Description | Return| File
|:--: | :-- | :--| :--|
|_f_add | adds the top two elements of the stack | No Return | add.c|
| addnode | add node to the head stack | No Return | addnode.c|
| f_div | divides the top two elements of the stack. | No Return | div.c|
| execute | executes the opcode | No Return | execute.c|
| free_stack | frees a doubly linked list | No Return | free_stack.c|
| main | monty code interpreter | 0 on success | main.c| 

### Examples

```console
$lexxyla> ls
basics.c    general.c  main.h  memory.c   shell.c
builders.c  helper.c   hsh          README.md  test
```

## Authors :black_nib:

[Oluwatomisin Rahman](https://github.com/tosman1) and [Favour Ocheja Ocheja](https://github.com/)

## Acknowledgements :pray:

All work contained in this project was completed as part of the curriculum for ALX Africa SE. ALX Africa is an online full-stack software engineering program that prepares students for careers in the tech industry using project-based peer learning. For more information, visit [this link](https://www.alxafrica.com//).

<p align="center">
  <img
   src="https://www.alxafrica.com/wp-content/uploads/2022/01/header-logo.png"
       alt="ALX Africa Logo"
  >
</p>


