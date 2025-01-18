# COBOL Numeric Overflow Bug

This repository demonstrates a common numeric overflow bug in COBOL programs.  The `bug.cob` file contains the erroneous code.  The `bugSolution.cob` file provides a corrected version.

## Description
The bug involves incrementing numeric fields without sufficient overflow checking.  In production systems this can lead to unexpected results and data corruption.

## Solution
The solution uses more robust techniques to prevent overflow.  Improved handling of numeric values includes validation checks, larger data types where appropriate, and potentially using a different data representation when the number of digits can be greater than the defined size.  Thorough testing is crucial to eliminate such issues.