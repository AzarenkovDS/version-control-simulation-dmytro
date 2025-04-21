# SBA: Version Control

## The steps you took to create and manage branches.
To create new branches, I used the `git checkout -b some-feature` command. After making changes, I staged them with `git add .` and committed using `git commit -m "message"`. Once the work on the feature was complete, I switched back to the main branch with `git checkout main` and merged the feature branch into the main branch using `git merge some-feature`.

## How you handled the merge conflict.
When I had a merge conflict while merging the header and footer branches, I edited the index.html file manually. I removed the helper comments that Git added to highlight the conflicting code. Then I adjusted the order of the code blocks, placing the footer below the header, since I had merged the footer branch first. After resolving the conflict, I staged the changes and committed them.


## How the pull request process helped you ensure code quality and collaboration.
After pushing my branch to GitHub, I created a pull request. It helped me review my own changes before merging. The pull request showed all modified files, which made it easier to understand what had been done. Pull requests are useful for team collaboration -they allow other developers to review the code, leave comments, and suggest improvements before merging to the main branch.
