# CO_Project-79
Implemented a Custom Simulator and Assembler for a hypothetical Instruction Set Architecture along with Visualization for Memory Access Location over Time  

# Assembly Language Interpreter

This Python script serves as an interpreter for a simple assembly language. It supports various instructions and handles variables, labels, and different types of commands. The script is designed to process and convert assembly-like code into machine code.

## Usage

1. **Input Format:**
   - Enter the assembly-like code line by line.
   - Labels, variables, and instructions are supported.

2. **Instructions:**
   - The supported instructions include 'add', 'sub', 'mul', 'xor', 'or', 'and', 'mov', 'ls', 'rs', 'div', 'not', 'cmp', 'ld', 'st', 'jmp', 'jlt', 'jgt', 'je', and 'hlt'.

3. **Variables and Labels:**
   - Declare variables using the 'var' keyword.
   - Labels end with a colon (':').

4. **Execution:**
   - The script processes the code in two passes - first for validation and second for conversion.
   - It checks for syntax errors, illegal instructions, and other issues.

5. **Output:**
   - The script outputs the machine code for each instruction.

## Code Structure

- `process_line(line, location)`: Processes each line of code during the validation pass.
- `convert_line(line, location)`: Converts each line of code into machine code during the conversion pass.
- Various functions for checking the validity of instructions, registers, variables, and labels.

## Running the Script

1. Execute the script: `python script_name.py`.
2. Enter the assembly-like code.
3. View the generated machine code.

## Example

```python
python script_name.py
