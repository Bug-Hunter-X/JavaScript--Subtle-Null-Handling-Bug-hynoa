# JavaScript: Subtle Null Handling Bug

This repository demonstrates a subtle bug in JavaScript related to null value handling. The function `foo` aims to add two numbers, but it incorrectly handles the case where one or both inputs are null or undefined.  While the code handles explicit null checks, it unexpectedly produces NaN when an undefined value is passed.