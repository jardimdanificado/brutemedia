# pixibruter

## Description

a pixilang based multimedia engine, implements a bruter interpreter and a set of tools. 


## Table of Contents

- [Installation](#installation)
- [Types](#types)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Installation

run ./build.sh then run pixilang on the build folder.

## Pixilang

Global Objects: variables, functions, constants.

## Types

- `$variable` = args that starts with $, can be anything, variables are stored in "variables"

- `number` = args that starts with 0, 1, 2, 3, 4, 5, 6, 7, 8, 9 or -

- `string` = any other args

## Usage

take a look at pixilang docs and src/ffi.pixi to get better understanding of the functions and usage


- argless functions:

`function;`


- returnless function:

`function arg1 arg2 ...;`


- function which return goes to $target_variable (":" denotes a return, the target variable must be on the left):

`target_variable:function ...;`


- argless function which return goes to $target_variable:

`target_variable:function;`


- variables always starts with $:

`function $variable_1 $variable_2 ...;`


## Contributing

[WORK IN PROGRESS]

## License

[WORK IN PROGRESS]
