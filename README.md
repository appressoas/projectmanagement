# Project management

This repo explains and shows how we handle, administrate and work with our projects when there is a given start and end date.
Look at `Issues` and `Projects` for detailed examples.

## General rules
1. New issues are just placed in the GitHub repo.
2. Never assign a new issue to a developer.
3. Only a project manager can add the labels `Customer backlog`, `Project backlog`, `Sprint backlog` or `Not relevant` to an issue.
4. Anyone can add a new issue to a project.

## Sprint rules
1. A sprint starts on monday morning, 8 o'clock, and lasts until the next thursday (10 days laster), 12 o'clock
2. The first assignment of every sprint is to decide which issues are to be completed during the sprint.
3. Planned issues which are not completed during the sprint are moved back to all issues on GitHub and labeled with "Sprint backlog" and "Not completed during sprint".
4. The first day after a completed sprint, the project manager and customer has a meeting where the work done during the sprint is presentated.
5. We use one GitHub project board for each sprint.
6. When estimating issues for a sprint, remember to include time for review and some overhead.
7. The project manager and developers may reorganize issues during a sprint if in need. (A bug occurred, something went wrong or other) 


## Responsibilities
Normally a project manager, developers and a customer are involved in a project.

### Customer responsibilities
1. Participate in the presentation with the project manager every other friday.
2. Decide toghether with the project manager new issues and which existing issues to remove in order to keep the budget and delivery time as written in the contract.

### Project manager responsibilites
1. The project manager is responsible for looking thru new issues GitHub, label them and move or close these new issues.
2. Present the work done during the last sprint for the customer. This presentation is friday morning after finishing a sprint. 
3. Decide toghether with the customer new issues and which existing issues to remove in order to keep the budget and delivery time as written in the contract.

### Project manager and developer responsibilities
1. Work thru the issues in the column “Sprint backlog” on the project board, and together decide which issues to be completed in the next sprint.
2. Fine tune and estimate work time for all issues to be completed during the sprint.
3. Move all issues to be included in a sprint from the column "Sprint backlog" to the column "Sprint".
4. Removes the column "Sprint backlog" when all inlcuded isses are moved.

### Developer responsibilities
1. Assigning issues to oneself and move the issue to the “Active” column when one starts working on the issue.
2. Move work which needs a review to the "Review" column and unassign oneself.
3. Review other developers work.
4. When a review is done, move the issue to the "Done" column and close the issue.
5. When a issue is completed but not in need of a review, move the issue to the column "Done" and close the issue.

## Repo labels
The following labels are used by the project manager
1. `Customer backlog`
2. `Project backlog`
3. `Sprint backlog`
4. `Not relevant`

### Label explenation
1. `Customer backlog` is used when an issue is relevant for the customer, but not to be included in the current project.
2. `Project backlog` is used when an issue is relevant for the project.
3. `Sprint backlog` is used when an issue is to be prioritiezed within the current project.
4. `Not relevant` is used when an issue is to be closed without any work.
