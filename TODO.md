Todo list for Google-Search-API
====

## Next tasks

- [x] Mock html test for search images - https://pypi.python.org/pypi/mock/
- [ ] Test and implement the use of images options in search images method (is broken right now, in the middle of a refactor)
- [ ] Refactor and split main module in separated ones
- [ ] Write tests for future methods development (they should failed and be skipped up to the proper method development moment)
- [ ] Be able to manage both Chrome and Firefox, and maybe Ie too, depending in what browser the user has
- [ ] Write a full suite of docs test and unit tests
- [ ] Reconvert all comments following the google python style guide - https://google-styleguide.googlecode.com/svn/trunk/pyguide.html

## Stuff to check out later on

* vcrpy to record web requests and make more automated mocks
* SauceLabs to do UI tests
* Sphinx to generate documentation - readthedocs style
* Cookiecutter-pythonpackage to make an instant and complete python package structure - https://github.com/audreyr/cookiecutter-pypackage and https://github.com/audreyr/cookiecutter
* PhantomJS to use browsers without actually opening them (works with selenium) - http://stackoverflow.com/questions/13287490/is-there-a-way-to-use-phantomjs-in-python
* Understand UTF-8 encoding in the context of getting html, writing it into a file and getting it back
* Make TODOs with an automatic application for sublime text that makes .todo files with awesome features
* Automatic PEP8/Flake8 formatting style when pushed to GitHub