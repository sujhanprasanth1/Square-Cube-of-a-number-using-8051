# Square-Cube-of-a-number-using-8051
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
MOV A,P0
MOV R0,A
MOV B,R0
MUL AB
MOV P2,A
END









```

## OUTPUT
<img width="715" height="440" alt="image" src="https://github.com/user-attachments/assets/fb9a93c7-69a1-4083-b48d-70e8d28b2594" />


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
MOV A, P0
MOV B, A
MUL AB
MOV R0, A
MOV A, R0
MOV B, P0
MUL AB
MOV P2, A
END








```


## OUTPUT
<img width="529" height="387" alt="image" src="https://github.com/user-attachments/assets/bb0b2c75-bb80-4c32-aa7d-4eaabceb3a18" />

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.


