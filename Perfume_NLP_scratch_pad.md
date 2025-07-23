# Project Scratch Pad Notes

## Lesson: Git can't do files larger than 100 MB
Issue: git couldn't push because a file was Too Large
My Fix: Remove the file!
New Issue: git can't push because that phantom file was Too Large
SOLUTION: https://stackoverflow.com/questions/33360043/git-error-need-to-remove-large-file
    "git filter-branch -f --tree-filter 'rm -f path/to/large_file_name' HEAD --all"
Side Notes: Evidently?? filter-repo is the updated version according the amount of Distressed Messages git provided to me when  I Ran This