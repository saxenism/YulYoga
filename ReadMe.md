# Yul Yoga (The best zero to hero Yul guide)

## About Yul (picked from documentation itself)

1. Yul provides for loops, if and switch statements
2. No explicit statements for SWAP, DUP, JUMPDEST, JUMP and JUMPI are provided (as they obfuscate data flow and control flow)
3. Statements such as mul(add(x, y),z) are preferred over 7 y x add mul, because it becomes easier to see which opcode is being used for which operand
4. Yul is desigend for a stack based machine (EVM) but it does not expose the programmer to the complexity of the stack itself
