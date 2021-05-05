## Contributing Guide

### Bug Reports

**1.** Ensure the bug was not already reported by by reading the [Issues](https://github.com/CookingWithCale/CookingWithCale/issues).

**2.** Open `/docs/bug_report_template.md` and copy it's contents to the clipboard.

**3.** Create an issue, paste the template into the Issue body and fill it out.

### Feature Requests

**1.** Same as the instructions for submitting a bug report except with using `/docs/feature_request.md`.

### Completing Issues

**1.** Clone the repo and create a branch for the IssueNuber:

```Console
git clone https://github.com/CookingWithCale/CookingWithCale.git
cd CookingWithCale
git checkout -b Issue123
```

**2.** Complete the issue with passing unit tests and submit the completed issue:

```Console
git add --all
git commit -m "ModuleID.Add feature XYZ. #123"
git push origin Issue123
```

**3.** Create a Pull Requesting using the `/docs/pull_request_template`

**4.** Get others to inspect your changes and merge the branch to the master.

**5.** Merge the branch, complete another ticket, and delete the old branch. Please note in the first example we used the command `git checkout -b Issue123` but this time we're going to recycle the git branch by moving it with the `git branch -m OldIssue NewIssue` command; it's less work than deleting the branch.

```BASH
git checkout -m Issue123 Issue125
git add --all
git commit "ModuleID.Fix feature ABC. #125"
```

**6.** Submit a Pull request on GitHub at <https://github.com/CookingWithCale/CookingWithCale/pulls>.

## License

Copyright 2014-21 © Cale McCollough <<https://cookingwithcale.org>>; most rights reserved, Third-party commercialization prohibited, mandatory improvement donations, licensed under the Kabuki Strong Source-available License that YOU MUST CONSENT TO at <https://cookingwithcale.org/License>.
