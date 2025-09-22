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
```asm
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
![WhatsApp Image 2025-09-22 at 20 51 03_28d05c51](https://github.com/user-attachments/assets/a0199e01-5d7f-4717-a9be-418760f7d542)

![WhatsApp Image 2025-09-22 at 20 51 17_3db4b16a](https://github.com/user-attachments/assets/0e06a59b-8e38-4c1b-a37f-7ed7375c9714)

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
```asm
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
![WhatsApp Image 2025-09-22 at 20 55 31_312985c1](https://github.com/user-attachments/assets/029d74b9-74fd-4309-a47e-5751059513ce)
![WhatsApp Image 2025-09-22 at 20 55 45_5633358b](https://github.com/user-attachments/assets/665ac3c7-5490-42e1-9313-2742d62d1868)


## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
