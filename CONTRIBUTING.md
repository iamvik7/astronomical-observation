# Contributing to examples
We want to make contributing to this project as easy and transparent as possible.

## Pull Requests
We actively welcome your pull requests.

### For new examples
0. Create a Github issue proposing a new example and make sure it's substantially different from an existing one.
1. Fork the repo and create your branch from `main`.
2. If you have added code that should be tested, add tests to 'run_python_examples.sh'.
3. Create a 'README.md'.
4. Add a card with brief description of your example and link to the repo to 'docs/source/index.rst' file and build the docs by running:

   ```
   cd docs
   virtualenv venv
   source venv/bin/activate
   pip install -r requirements.txt
   make html
   ```
   when working with 'virtualenv', run 'deactivate'.

5. Verify that there is no issues in your build. You can check the preview locally by installing [sphinx-serve](https://pypi.org/project/sphinx-server/)
   then running 'sphinx-serve -b build'.

6. Ensure your test passes locally.
7. If you haven't already, complete the Contributor License Agreement.
8. Address any feedback in code review promptly.

## For bug fixes
1. Fork the repo and create your branch from 'main'.
2. Make sure you have a GPU enabled machine, either locally or in the cloud. 'g4dn.4xlarge' is a good starting point on AWS.
3. Make your code change.


## Contributor License Agreement (CLA)
To accept your pull request, we need to submit a CLA. You only need to do this once to work on any of Facebook's open source projects.

## Issues
We use Github issues to track public bugs. Please ensure your description is clear and has sufficient instructions to be able to reproduce the issue.














   
