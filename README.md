This homework is due by the end of the day on September 25th 2019.

1.  Create an R package called `linearmodel`.
2.  Implement the `linear_model()` function and document it. It should
    take a formula, a data frame and a list of constasts for factor
    variables as input.
3.  Add a data.frame called `lm_patho` as a data set to the package. Use
    the `lm_path.csv` for the data. Create a `data-raw` directory in
    your package (hint: use `usethis::use_data_raw()` and
    `usethis::use_data()`) to add it to the package. Don’t forget to
    document it.
4.  Add the `test-linear-model.r` file to your regression testing (hint:
    use `usethis::use_testthat()` to create the directory structure).
    Make sure your implementation passes the tests.
5.  Implement gradient descent for ordinary least squares.
6.  Write test code for your gradient descent function.
 
<!--
5.  Add the package to [Travis-CI](https://travis-ci.com/) and update
    the `README.md` file so that the badge points to your Travis build
    (hint: use `usethis::use_travis()`). You will know it is working
    when the badge is green and gives the message “passing”. Exra hint:
    sign up for the Github student pack.
6.  Add code coverage (with either [Coveralls](https://coveralls.io/) or
    [CodeCov](https://codecov.io/)). Hint use `usethis::use_coverage()`).
-->
