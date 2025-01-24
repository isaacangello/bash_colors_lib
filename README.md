# Bash Colors Library

## Overview

The Bash Colors Library is a simple and lightweight library designed to add color and style to your Bash scripts. It provides a set of predefined functions and variables that make it easy to apply various colors and text styles to your terminal output.

## Features

- Easy to use functions for applying colors and styles
- Supports a wide range of colors
- Includes text styles such as bold, underline, and blink
- Lightweight and fast

## Installation

To use the Bash Colors Library, simply source the `bash_colors_lib` file in your script:

```bash
source /path/to/bash_colors_lib
```

## Usage

Here are some examples of how to use the library:

```bash
# Print text in red
echo -e "${red_bd}This is red text$"

# Print bold text
echo -e "${b_red_bd}This is bold text"

# Print underlined text
echo -e "${u_red_bd}This is underlined text$"
```
### #################################################################################
## Available Styles using prefix
### #################################################################################

- `b_ == BOLD`  
- `u_ == UNDERLINE`
- `f_ == BLINK`
- `NC or nc` (No Color - resets the text to default)


Number| Styles |prefix
 00: |Nenhum |               none
 01: |Negrito(bold)|         b_
 04: |Sublinhado(Underline)| u_
 05: |Piscante |             f_
 07: |Reverso(Reverse)|      r_
 08: |Oculto(Hidden)|        h_

### ##################################################################################
## Available text Colors
### ##################################################################################

- `black == BLACK`
- `red == RED`
- `green == GREEN`
- `yellow == YELLOW`
- `blue == BLUE`
- `magenta == MAGENTA`
- `ciano == CYAN`
- `white == WHITE`



 --|(Text Colors)|--

 30:| Preto|                 black
 31:| Vermelho|              red
 32:| Verde  |               green
 33:| Amarelo |              yellow
 34:| Azul|                  blue
 35:| Magenta (Rosa)|        magenta
 36:| Ciano (Azul Ciano)|    ciano
 37:| Branco|                white


### ##################################################################################

## Available Background Colors

### ##################################################################################

 --|Background colors|sufix
 00:| none |                 _  (Only underscore )
 40:| (Black)Preto|                 _bd (dark)
 41:| (Red)Vermelho|              _br
 42:| (Green)Verde |                _bg
 43:| (Yellow)Amarelo |              _by
 44:| (Blue)Azul |                 _bb
 45:| (Rosa)Magenta (Rosa) |       _bm
 46:| (Ciano)Ciano (Azul Ciano) |   _bc
 47:| (white)Branco |               _bw


## License


This project is licensed under the general Public License.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue if you have any suggestions or improvements.

## Contact

For any questions or inquiries, please contact [isaacangello@inf.ufpel.edu.br].
