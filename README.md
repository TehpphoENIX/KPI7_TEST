# README example

Sample text

## Merge conflicts

Try to merge branches 1a and 1b, 2a and 2b, 3a and 3b.

1. 1a and 1b have classic line conflict: line is modified diferently in branches 1a and 1b which results in conflict.
2. 2a and 2b have other type of conflict: in 2a file is modified and in 2b file is deleted.
3. 3a and 3b have no conflict: in 3a file is not modified but in 3b file

| 1 branch         |         2 branch |    conflict |
|------------------|------------------|-------------|
| 1a file modified | 1b file modified | conflict    |
| 2a file modified | 2b file deleted  | conflict    |
| 3a original file | 3b file deleted  | no conflict |
