# PHP Foreach Loop and Unset() Bug

This repository demonstrates a common, yet subtle, bug in PHP when using `unset()` within a `foreach` loop on an array.  The issue arises because modifying the array during iteration can cause unexpected skipping of elements or incorrect results. 

The `bug.php` file shows the problematic code and its output.  The solution (`bugSolution.php`) illustrates a more robust approach.

This is a great example of why careful consideration of array manipulation within loops is crucial to avoid hard-to-detect errors.