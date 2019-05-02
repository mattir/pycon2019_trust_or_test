# To trust or to test?:
## Automated testing of scientific projects with pytest

---

Repo for the Trust or test tutorial. Presented by Dorota Jarecka, and Anna Jaruga

### Description

Many researchers rely strongly on numerical computations. Unfortunately, testing scientific code is a hard task. Often there is no ground truth available for comparison and the end result of the simulation is unknown even to the code developer herself/himself. Often the user-base of the scientific code is small and the work environment does not provide incentives for testing.

However, there are always parts of the code that are relatively easy to cover by Unit Tests. Scientific pipelines could and should have Regressions Tests, which ensure that previously developed software still performs after changes in the code, or in external libraries and computational environment. An automatic test suite should not be a burden and can become a game-changer even for a small programming project.

This tutorial is meant to be an introduction to testing in general and to pytest library. Pytest is a full feature tool to test the Python code, it offers a simple way to get started and scales from simple unit testing to complex functional testing. We will begin with simple assert statements and finish with pytest.fixture and pytest.parametrization. The tutorial will also cover a simple integration of the tests suit with Continuous Integration platforms using GitHub and Travis/CircleCI.
