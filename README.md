# gitRVN
Ideas and project around incentivizing development with RVN

The idea is to have a platform that helps automate the coordination of offering RVN for the completion of GitHub issues.  It is currently for fulfilling the needs of the RavencoinFoundation to use the donated funds to incentivize Ravencoin related projects.

The manual MVP of this is to add human-readable and machine-readable comments on issues with the promise to pay for completion of the issues.  Update status manually as developers pick up issues, or comment that they will.  This could be automated by a developer writing status=reserved in an issue comment.

Further development could include:
* Automating adding issue comments
* Automating e-mail notifications of new funded issues
* Triggering the issue comment to - "in-progress" when someone takes on an issue to prevent duplication of effort.
* Prompting for updates or removal of developer from an issue if no progress.
* Automating the W9 or W8-BEN request for completed work.
* Status updates for open, in-progress, completed, paid.
* API for querying the open funded issues and their status

If you, as a developer, are working on any of these issues or projects, please e-mail tron@ravencoin.foundation so the status can be changed to in-progress so we can avoid race-conditions, wasted efforst, and hurt feelings if two developers tackle the same code.  Better automation will be created if these notifications become too much to manage manually.

## Projects and Issues with Funding - https://ravencoin.foundation/proposals/


Adding to issue comment:
```
amount=USD$2000.00
paid_in=RVN
status=open
info=https://github.com/RavencoinFoundation/gitRVN
```
