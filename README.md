# cloud-native-hw2

First, create a repo on Github, add the default `README.md`. Clone it to local.

Create two branches `hw1-p` and `hw1-f` and push them directly.

Go Settings->Features->Issues->Set up templates, create a bug report template. Use the template to create an issue.

Navigate to Actions, click New Action and create a "Simple workflow" by Github. Modify the yaml file so that it runs `main.sh` with bash.

Create the `main.sh` and push it to test if the workflow run correctly.

Modify `main.sh` on `hw1-p` and `hw1-f`, for the success one, just add some dummy echoes. However, for the failed one, it is necessary to change the exit code to make the action fail.

Finally, push the two branches, open pull requests on them, and the actions will run automatically. Comment something arbitrary to fit the last requirement.
