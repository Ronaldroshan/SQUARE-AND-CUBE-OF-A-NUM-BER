# SQUARE AND CUBE OF A NUMBER
# 8051 Square  Program

## AIM
To write and execute an Assembly language program for finding the square of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value to Port 0 (P0).
3. Execute the program.
4. The output square value is stored in Port 2 (P2).

## PROGRAM
```
ORG 00H
MOV R0,#40H
MOV A,@R0
MOV B,A
MUL AB
INC R0
MOV @R0,A
INC R0
MOV @R0,B
END
```

## OUTPUT
![WhatsApp Image 2025-10-08 at 08 58 38](https://github.com/user-attachments/assets/0dec94eb-ee38-4241-8c34-e82c0c4235be)


## RESULT
Thus, the square of the given data is calculated using 8051 Keil.

# 8051 Cube  Program

## AIM
To write and execute an Assembly language program for finding the cube of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value.
3. Execute the program.
4. The output cube value is stored in a memory location.

## PROGRAM
```

ORG 00H
MOV R0,#40H
MOV A,@R0
MOV B,A
MUL AB
MOV B,@R0
MUL AB
INC R0
MOV @R0,A
INC R0
MOV @R0,B
END
```


## OUTPUT
![WhatsApp Image 2025-10-08 at 08 58 38 (1)](https://github.com/user-attachments/assets/d011a554-15f2-49af-b58c-aa77e8e2e500)

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
