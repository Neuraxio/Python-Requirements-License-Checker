# Python Requirements License Checker

## Instructions

To add the license checker to your project, do the following when your console is located in the root of your project in your local computer: 

```bash
git remote add license-checker github.com/Neuraxio/Python-Requirements-License-Checker
git checkout license-checker
git pull origin license-checker license-checker
git checkout master
git merge license-checker
git push origin master
```
## Example

You can see an example of the action in the example branch. Do not use the python python_license_checker.yml file in that branch because it has been modified to execute on push and pull request on that specific branch.
