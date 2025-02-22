# Unhandled Exception in TypeScript Arithmetic Operations

This repository demonstrates a common error in TypeScript: unhandled exceptions.  The `divide` function throws an error if the divisor is zero, but the calling code doesn't handle this possibility. The program crashes if `divide` is called with a zero divisor.

The `bug.ts` file contains the erroneous code.  The `bugSolution.ts` file provides a corrected version that uses a `try...catch` block to handle the exception gracefully.