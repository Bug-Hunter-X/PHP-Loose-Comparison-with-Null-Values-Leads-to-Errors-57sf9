# PHP Loose Comparison Bug

This repository demonstrates a common error in PHP related to loose comparison (==) with null values.  Using loose comparison when dealing with potentially null parameters can lead to unexpected behavior and hard-to-debug issues.

The `bug.php` file contains the problematic code. The `bugSolution.php` file shows the corrected version using strict comparison (===).