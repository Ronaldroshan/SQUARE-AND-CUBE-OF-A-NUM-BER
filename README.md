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
MOV R0,#60H
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

<img width="490" height="428" alt="image" src="https://github.com/user-attachments/assets/81b7bb8e-7dcf-4db5-8925-c2b09b769fd3" />

<img width="736" height="379" alt="image" src="https://github.com/user-attachments/assets/1b6829b9-b95b-4b88-864c-1df499e189cd" />

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
MOV R0,#60H
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

<img width="516" height="515" alt="image" src="https://github.com/user-attachments/assets/dd05e72f-5697-4c86-8987-ede4e97eb1ac" />

<img width="665" height="335" alt="image" src="https://github.com/user-attachments/assets/a5a61077-ef5b-45e0-925c-7eb2bfbc0ad0" />
