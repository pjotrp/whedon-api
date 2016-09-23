# Whedon API

A small service that provides the basic Whedon API

### Here are some things that Whedon can do:

```
# List all of Whedon's capabilities
@whedon commands

# Assign a GitHub user as the reviewer of this submission
@whedon assign @username as reviewer

# List the GitHub usernames of the JOSS editors
@whedon list editors

# List of JOSS reviewers together with programming language preferences and domain expertise
@whedon list reviewers

# Change editorial assignment
@whedon assign @username as editor

# Set the software archive DOI at the top of the issue e.g.
@whedon set 10.0000/zenodo.00000 as archive

# Open the review issue
@whedon start review
```
