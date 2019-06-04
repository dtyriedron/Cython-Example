# cythonexample
Trying out cython and testing the speed compared to the same code done in python.

- In testing.py two compilation times are compared based on two different file types .py and .pyx and then the difference between the two files are printed.
- The difference between the files example_cy.pyx and example_py.py are timed.
- The results from the testing.py file are shown in the testResults.txt file.
- C and C++ files are also created as bi-product allowing for python to be used to speed up development of such languages.
- The html file can be viewed in a browser to allow people to see the translation to C from python on each line of the code.

## Running the test yourself

- To run the test yourself you need Python, this can be downloaded online.
- Once Python has been downloaded you will need to also get cython using the command: "pip install cython" in a terminal/cmd.
- Then run the command: "python setup.py build_ext --inplace" to build.
- Then run the command: "python testing.py" to compile.
- The output should then be returned.

