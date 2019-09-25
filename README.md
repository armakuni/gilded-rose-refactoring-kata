# The Golden Master

Adding tests to legacy code, with some speed!

> ======================================
> Gilded Rose Requirements Specification
> ======================================
> 
> Hi and welcome to team Gilded Rose. As you know, we are a small inn with a prime location in a
> prominent city ran by a friendly innkeeper named Allison. We also buy and sell only the finest goods.
> Unfortunately, our goods are constantly degrading in quality as they approach their sell by date. We
> have a system in place that updates our inventory for us. It was developed by a no-nonsense type named
> Leeroy, who has moved on to new adventures.

This introduction, and this Kata is taken from [emilybache](https://github.com/emilybache/GildedRose-Refactoring-Kata) and this Kata was originally created by [Terry Hughes](https://github.com/NotMyself/GildedRose)

This is a great Kata to use if you wish to experiment with different ways of testing legacy code.

## Getting Set Up

```pipenv install``

## Running the Tests

``` pipenv run pytest --cov-report html:cov_html --cov=gilded_rose --approvaltests-use-reporter='PythonNative' ```

## Your Challenge

1. Run the tests
1. Open coverage file ```cov_html/index.html```
1. Modify the return_fixture in test_approval.py until you get 100% code coverage

## Your Challenge (continued)

1. Refactor the code!