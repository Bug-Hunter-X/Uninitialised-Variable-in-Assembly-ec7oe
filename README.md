This repository demonstrates a common error in assembly programming: using an uninitialized variable.  The bug.asm file contains code that attempts to subtract 30 from the ebx register before it has been initialized.  This leads to unpredictable results, depending on the prior contents of ebx.  The bugSolution.asm file provides a corrected version of the code.