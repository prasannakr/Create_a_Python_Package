# Create_a_Python_Package
First attempt at creating Matrix operations using Python Object Oriented Program (OOP)

Aim to accomplish the following using Udacity workspace:
1. Get the user to input matrix values.
2. Perform Addition/Subtraction/Multiplication of matrices
3. Check to see if both matrices are of same rank(rows, columns)

Terminal commands used:<br>
cd package<br>
python setup.py sdist<br>
pip install twine<br>
twine upload --repository-url https://test.pypi.org/legacy/ dist/*
pip install --index-url https://test.pypi.org/simple/ dsnd-probability

Test package to install
pip install -i https://test.pypi.org/simple/ matrix-package-krp
