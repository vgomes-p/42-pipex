![cover](images/cover-pipex.png)
## O pipex é um projeto em C que replica o funcionamento do operador de pipe (|) no shell. Ele conecta a saída de um comando à entrada de outro, permitindo a execução encadeada de processos.

### Data de início:
Eu iniciei o trabalho na pipex dia 29 de Novembro de 2024.
### Data de entrega:
Validei o projeto no dia 13 de Dezembro de 2024.

![print_intra](images/pipex.png)

# RUNNING PIPEX
## Requirements
#### - Linux, macOS or Windows with WSL installed
#### - cc or another compatible compiler
#### - 'make' installed
### 1 - Clone this repository
```bash
git clone https://github.com/vgomes-p/pipex-42.git
```

### 2 - Get into the project dir
```bash
cd pipex-42/project
```

### 3 - Run the command make
```bash
make
```

### 4 - Now call the program and the commands you want to run
> There are a few tests you can run on the "tests to run.txt" file which is in the project folder. To run these tests, you will need the file named "infile" (also present in the project folder)
#### Example 1:
```bash
./pipex Makefile "cat" "grep NAME" outfile_3_0
```
#### Example 2:
```bash
./pipex infile "ls" "wc -l" outfile_3_4
```

# CLEANING PIPEX
### 1 - Go to the main dir
```bash
cd pipex-42/project
```
### 2 - Run the command clean or full clean
```bash
make clean
```
or
```bash
make fclean
```

### 3 - Close the terminal
```bash
exit
```