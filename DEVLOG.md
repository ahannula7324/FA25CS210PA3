### Devlog Entry 1
Date: 5/4/26

Issue: Says "No path exists" when running dfs. This means it did not visit cells correctly.

Attempts: The maze setup generated correctly, however realized I was missing a crucial piece of code.

Resolution: Added visited[row][col] = true; to the beginning of the function to allow for it to mark visited correctly.

### Devlog Entry 2
Date: 5/4/26

Issue: DFS runs, however printPath() is not working correctly with DFS. This caused an infinite/never ending code.

Attempts: Each cell is assigned incorrectly, so every time I run, an error keeps occuring.

Resolution: I changed parent_r[newRow][newCol] = newRow, to having it equal row. I did the same with col as well, as prior, they were both pointing to themselves.

### Devlog Entry 3
Date: 5/5/26

Issue: Structure of program was not running.

Attempts: I tried restarting CLion, and explored changes inn my settings and name of project to get it to run.

Resolution: I realized I needed a CMakeLists.txt file to allow my main.cpp file to run correctly. After fixing this problem I was finally able to run my program and get outputs.

