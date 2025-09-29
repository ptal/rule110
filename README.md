# Cellular Automaton: Rule 110

The code will be compiled with the following command to obtain the best performance:

```
g++ rule110.cpp -Wall -Werror -Wextra --pedantic -std=c++23 -march=native -DNDEBUG -O3 -o rule110
```

Make sure your code compile with this command before submitting for review.

For debugging your code, you can compile with this command:
```
g++ rule110.cpp -Wall -Wextra --pedantic -std=c++23 -g -o rule110
```

## Tests

The `data` directory provides some test files to verify the correctness of your program. For every test there are 3 files:
- `automaton_<num>.txt`: initial configuration file.
- `pattern_<num>.txt`: pattern file.
- `output_<num>.txt`: contains the expected result/output of your program for a simulation of `100` steps.

Note: The only files used by your code are the `automaton` and `pattern` file.