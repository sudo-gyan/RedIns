# KWOC 2020

### Project Name: TITANIC SURVIVAL EXPLORATION
### Mentor : Prashant Sengar

#### Project Description: Script to download media from Reddit and post them on Instagram, Twitter and Facebook.

Project Repository: https://github.com/prashantsengar/RedIns

### About KWOC:
Kharagpur Winter of Code is a 5-week long online programme for the students, who are new to open source software development. The programme not only helps students to get involved in open source, but also preps them for many open source summer programmes, Google Summer of Code being one of them.  

### Some Info About My Project
I chose the project [RedIns](https://github.com/prashantsengar/RedIns) for KWOC and selected to work on issue [#5](https://github.com/prashantsengar/RedIns/issues/5). The primary aim was to use [RedPy](https://github.com/prashantsengar/RedPy) (another project of Prashant Sengar to download Reddit images and videos) in [RedIns](https://github.com/prashantsengar/RedIns) such that it will be easier to maintain and remove redundancy.

### Contribution #1
There were several issues with [RedPy](https://github.com/prashantsengar/RedPy) code which was made to a single [issue](https://github.com/prashantsengar/RedPy/issues/1).

The initial [PR](https://github.com/prashantsengar/RedPy/pull/2) was to fix those issues.

Some of the issues that were fixed are:
- Packaging dependencies in `setup.py`.
- Fixed importing issues.
- Removed hardcoded paths.
- Handled several errors and exceptions.
- Exposed certain functions to make integration with [RedIns](https://github.com/prashantsengar/RedIns) easier.

# Contribution #2
After fixing [RedPy](https://github.com/prashantsengar/RedPy) I started to work on [RedIns](https://github.com/prashantsengar/RedIns)

There were several issues here my main focus was [#5](https://github.com/prashantsengar/RedIns/issues/5). I tried to solve most of it in the [PR #15](https://github.com/prashantsengar/RedIns/pull/15).
The issues I tried to fix were [#1](https://github.com/prashantsengar/RedIns/issues/1), [#3](https://github.com/prashantsengar/RedIns/issues/3), [#5](https://github.com/prashantsengar/RedIns/issues/5).

The changes that were done were :
- Fully restructured code to use OOP structure.
- Added RedPy to download Media.
- Config structure was changed.
- Added more customizations that user can use.
- Made code more readable.
- Added deepsource to track codequality and vulnerabilities.

### Verdict
I want to thank Prashant Sengar for his guidance in this project. It was a great learning experience for me . I want to thank KOSS, IIT KGP for conducting this beginner friendly program . This program helped me to learn what open source projects are and how to contribute to them.
