# Guidelines

## Branch naming

There are different types of branches:
* feature
* fix
* refactor

You must create your branch accordingly to its type:
| Branch Type | Name Format                                    |
| :---------- | :--------------------------------------------- |
| Feature     | `feat/{{issue_number}}-{{feature_title}}`      |
| Fix         | `fix/{{issue_number}}-{{fix_title}}`           |
| Refactor    | `refactor/{{issue_number}}-{{refactor_title}}` |

:warning: `{{issue_number}}` you should replace this, with the ID of the issue

## Pull request

The pull request you create must be understandable and must be linked to an issue.  
The pull request template is here to help you.

## Miscellaneous

> :warning: Avoid useless commits, otherwise before the pull request please squash them!

> :warning: When your issue is finished, the associated pull request must be tested.

> :warning: To validate your pull request you need 2 internal reviewers and 1 external reviewer.

> :warning: When the pull request is validated please use the Rebase and merge option.

> ℹ️ CI doesn't allow to merge pull request that doesn't pass all the tests or doesn't pass linter configuration (depending on the project).
