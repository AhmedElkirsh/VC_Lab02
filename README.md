# Ahmed Atef Ahmed Ibrahim 

## How to remove branches locally and remotely.

```
// locally
git branch -D test  // because the branch is not fully merged with main branch we use -D instead of -d
git branch -D dev

// remotely
git branch --delete test
git branch --delete dev
```

## How to checkout another branch without commit changes.

we use 'git stash'

```
// assume we are on dev branch and we have uncommited changes
git stash
git checkout main
```

## How to list tags.

```
git tags
```

## How to delete a tag locally and remotely.

```
// locally
git tag -d v1.7
// remotely
git push origin --delete v1.7
// or
git push origin :v1.7
```
## Adding an image in the README.md file.

![ITI Logo](https://logodix.com/logo/1926702.png)
