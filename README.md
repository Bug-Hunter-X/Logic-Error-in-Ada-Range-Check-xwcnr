# Ada Range Check Logic Error

This repository demonstrates a common logic error in Ada programs. The `Check_Range` function accurately checks whether an integer falls within a specified range. However, the `Main` procedure fails to correctly handle cases where the input integer is outside the defined range. This leads to the program always outputting that the number is out of range, regardless of the actual value.

The solution involves improving the handling of the function's return value in `Main`.  The solution file (`bugSolution.ada`) provides a corrected version that addresses this issue.
