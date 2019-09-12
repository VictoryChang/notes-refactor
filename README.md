# refactor
(pylint throughout)
0. Move code into a Git Repository (if not already done so)
1. conda 3.6 environment
  * https://docs.conda.io/en/latest/miniconda.html
  * conda create -n **envname** python=3
2. clone and checkout branch
3. pycharm
 * Choose Interpreter @ echo $CONDA_PREFIX
4. code flow + documentation
5. pycharm auto format (fixes some pep8 and linting issues automatically)
6. module level, removing dead code throughout
7. method level
8. functions level
9. nomenclature
10. modularization
11. addition of unit tests (including external apis that can later be refactored)
12. mypy params and returns (code level documentation)
13. doc strings
14. sphinx doc (help expose the library apis)
