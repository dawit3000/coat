## Test environments
* Windows 11, R 4.4.0
* R-hub: Windows, Ubuntu, Fedora (R 4.3.2)
* GitHub Actions (macOS-latest, ubuntu-latest, windows-latest)

## R CMD check results
0 errors ✔ | 0 warnings ✔ | 0 notes ✔

## Package purpose
The `coat` (Compensation Analysis Tool) package calculates overload compensation for college instructors based on institutional policies. It identifies credit hour overloads, applies enrollment-based proration, and generates clear, human-readable summary tables. The tool ensures fairness, consistency, and reduces administrative errors in faculty compensation.

## Submission notes
This is the first submission of the `coat` package to CRAN.

* All functions are documented and include runnable examples.
* A walkthrough vignette (`coat-walkthrough`) is included and builds correctly.
* The prior NOTE about an invalid file URI in `NEWS.md` has been resolved by removing the file path reference.
* A description of the compensation methodology has been added to the `Description` field, referring to the package vignette and a forthcoming R Journal article as suggested by Uwe Ligges.

## Reverse dependencies
This is a new package, so there are no reverse dependencies.

