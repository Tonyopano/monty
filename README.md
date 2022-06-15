# **Monty**


# Description:
monty is an interpreter of Monty ByteCodes files, which is a scripting language just like Python

## About the Monty language
This is a language that contains specific instructions to manipulate data information (stacks or queues), where each instruction (called opcode) is sended per line. Files which contains Monty byte codes usually have the .m extension.
## **Usage**
1. Clone the repository
     
     ```https://github.com/Aysuarex/monty```
2. Enter the directory
    
    ```cd monty```
3. Compile
 
 ```gcc -Wall -Werror -Wextra -pedantic *.c -o monty```
4. Execute:

    ```
    ./monty file.m
    ```
The file contains the bytcode instructions for example
   ```
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
## <u> Functions </u>
The functions used are:
| Name | Description | Return | File |
|:-----|:-----------:|-------:|------:|
|_f_add |adds the top two elements of the stack| No Return |add.c |
| addnode | add node to the head stack | No Return | addnode.c |
| f_div | divides the top two elements of the stack. | No Return | div.c |
| execute | executes the opcode | No Return | execute.c |
| free_stack | frees a doubly linked list | No Return |	free_stack.c |
| main | monty code interpreter | 0 on success | main.c |



## AUTHORS 
* **Suara Ayomide**

* **Chukwuoma Chizoba**

