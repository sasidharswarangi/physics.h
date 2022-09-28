# HOW TO CONTRIBUTE TO THIS PROJECT

## follow this process in order to contribute:

1. Communicate to us the feature, change or fix that you want to add or change by creating and issue with the template of "Feature, change or fix request"

3. Ask to us if you can be assigned to the issue and wait for our answer

**if we assigned to you the issue, then:**

3. Fork the project, clone your fork, and configure the remotes:

```
# Clone your fork of the repo into the current directory
git clone https://github.com/<your-username>/physicspy.git
# Navigate to the newly cloned directory
cd physicspy
# Assign the original repo to a remote called "upstream"
git remote add upstream https://github.com/nilis24/physicspy.git
```

If you cloned a while ago, get the latest changes from upstream:

```
git checkout main
git pull upstream main
```

4. Create a new topic branch (off the main project development branch) to contain your feature, change, or fix:

```
git checkout -b <topic-branch-name>
```

and commit your changes in logical chunks. Please use descriptive commit messages.

> Note:
> 
> The topic branch name should be in this format:
> 
> *dev-[your username]*


5. Locally merge (or rebase) the upstream development branch into your topic branch:

```
git pull [--rebase] upstream main
```

6. Push your topic branch up to your fork:

```
git push origin <topic-branch-name>
```

7. Open a Pull Request with a clear title and description against the main branch.

## bug reporting

if you've seen a bug in the code, please open an issue with the template "bug report"

Then we will be discussing in the comments of the issue the problem, and then if is a really bug this issue will be transformed into a issue of "Feature, change or fix request" and then we wil follow the contributing process.