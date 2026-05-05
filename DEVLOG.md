### Devlog Entry 1
Date: 5/4/26

Issue: Says "No path exists" when running dfs. This means it did not visit cells correctly

Attempts: The maze setup generated correctly, however realized I was missing a crucial piece of code.

Resolution: Added visited[row][col] = true; to the beginning of the function to allow for it to mark visited correctly.
