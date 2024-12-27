This repository demonstrates a subtle bug in R related to subsetting data frames using logical vectors.  When a logical vector used for subsetting is longer than the number of rows in the data frame, R silently truncates the vector without issuing a warning. This can lead to incorrect results that are difficult to trace. The `bug.R` file contains the buggy code, while `bugSolution.R` offers a solution to prevent this issue.