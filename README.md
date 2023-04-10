# senior-thesis
Data and code for Nishant's 2023 Senior Thesis

PYTHON FILES
1. spanningtrees: calculating and plotting various spanning trees on the airport network (Section 3.1)
2. hubs: single-objective hub selection, multi-objective hub selection, and hub creation (Sections 3.2, 3.3)
3. genericmodel: GUROBI optimization for generic hub selection model (Section 3.4)

DATA FILES (which are accessed by python code)
1. airports100: data for 100 highest-traffic airports in the contiguous US, which were used throughout this thesis
2. demandMatrix: 100x100 matrix representing travel demand between any two airports i and j
3. fareMatrix: 100x100 matrix representing average passenger fare between any two airports i and j
4. lengthMatrix: 100x100 matrix representing distance in miles between any two airports i and j
5. usaOutline: list of coordinate pairs used to create an outline of the contiguous US; useful for plotting maps

Please contact singhal@princeton.edu and singhal@alumni.princeton.edu with any questions!
