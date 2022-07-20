# GIT-playfround

GIT [practice for fun]

## upload changes:
git add -A
git commit -m 'new upload'
git push

## create a feature branch:
git checkout -b feature/prepMerge1
{ manually add a file }
up ( upload changes )
git push --set-upstream origin feature/prepMerge1
git checkout main
git merge feature/prepMerge1

## Cherry pick from a feature branch:
