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
 MOV DPTR,#4500H
 MOVX A,@DPTR
 MOV B,A
 MUL AB
 INC DPTR
 MOVX @DPTR,A
 INC DPTR
 MOV A,B
 MOVX @DPTR,A
END

```

## OUTPUT
<img width="1170" height="694" alt="image" src="https://github.com/user-attachments/assets/ef9f7963-bcdf-4294-afcb-0c8b94ba0e1e" />

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
 MOV DPTR,#4500H
 MOVX A,@DPTR
 MOV B,A
 MUL AB
 MOV B,A
 MOVX A,@DPTR
 MUL AB
 INC DPTR
 MOVX @DPTR,A
 INC DPTR
 MOV A,B
 MOVX @DPTR,A
 END
```


## OUTPUT
<img width="1179" height="715" alt="image" src="https://github.com/user-attachments/assets/b0a65536-9872-4715-8a4c-5e6fe7d1b7c1" />


## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
