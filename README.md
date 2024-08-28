# FauxPy_Detect_Errors
Use FauxPy and Python to detect Localization and more information of logic bugs in blocks of code.



run the following command to detect the errors:

python3 -m pytest -s -v tests/test_equilateral.py::test_equilateral_area_with_faulty_code --src code --family sbfl --granularity statement
