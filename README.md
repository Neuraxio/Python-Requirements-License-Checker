# Python Requirements License Checker

## Installation Instructions

To add the license checker to your project's main branch, assuming your main branch is called `main`, do the following when your console is located in the root of your GitHub project in your local computer: 

```bash
git remote add license-checker git@github.com:Neuraxio/Python-Requirements-License-Checker.git
git fetch --all
git checkout action
git pull license-checker action
git checkout main
git merge action --allow-unrelated-histories
git push origin main
```

You may edit the line 4 and 7 of your copy of the file `./.github/workflows/python_license_checker.yml` to change the branch on which the action happen. 

You may as well change the checked licenses at lines 13-18 of `./.github/workflows/license_checker_v2.py`. 

## Example

You can see an example of the action in the example branch. Do not use the python `python_license_checker.yml` file in that branch because it has been modified to execute on push and pull request on that specific branch only. You can push changes to the `requirements.txt` file of your fork or copy of this example branch to test it and visualize the checks in your project's GitHub UI.
