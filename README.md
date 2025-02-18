# CSS Float Overflow Bug

This repository demonstrates a common issue with using `float: left` in CSS where the parent container doesn't automatically adjust its size to accommodate its floating children.  This can lead to unexpected overflow of the content.

The `bug.css` file contains the problematic CSS code.  The `bugSolution.css` file provides a fix using the clearfix technique.