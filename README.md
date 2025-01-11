# 24-25 Senior Design Project

## Description
TBD

## Repo Layout
The `main` branch is the current most up-to-date version of the project.

Each branch represents a a different assigned portion of the project in the format...
> `a<#>-<assignment_name>`  

When software development begins, each feature will be in the format...
> `f<#>-<feature_name>`

Merging an assignment or feature branch will follow the following steps...
1. Increment the [version number](#version-history)
2. Merge `main` into the `assignment`/`feature` branch
3. Resolve any merge conflicts that may arise.
4. Test code to ensure functionality. 
5. Merge the `assignment`/`feature` branch into `main` with the following command: `merge --squash <branch_name>`. The merge commit message should include the version number (if it changes) and any change details.

If there is a quick fix that needs to be made to `main` then a new commit can be created directly on `main` so long as the commit message is `fix: <commit message>`.       

Versions shall be indicated with the following scheme `vA.B.C` where `A` is the major release number (at 0 until first release), `B` is the minor version number (incremented when `assignment` and `feature` branches are merged), `C` is the revision number which may be incremented for incomplete or partial features. 

## Getting Started
TBD

## Authors
Sean A Bridge - (513) 725-8525 - bridgesn@mail.uc.edu (school) -  bridgesa2020@gmail.com (personal)

## Version History
- 0.0.0
  - Initial License and README layout 

## License
This project is licensed under the GNU GENERAL PUBLIC LICENSE (v3.0, 2007) - see the [LICENSE](./LICENSE) file for details