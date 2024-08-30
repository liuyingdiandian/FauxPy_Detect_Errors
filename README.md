# FauxPy_Detect_Errors
Use FauxPy and Python to detect Localization and more information of logic bugs in blocks of code.



run the following command to detect the errors:

python3 -m pytest -v tests/test_equilateral.py --src code --family sbfl --granularity statement
python3 -m pytest -s -v tests/test_equilateral.py --src code --family sbfl --granularity statement
