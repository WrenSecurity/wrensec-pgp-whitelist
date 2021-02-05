# PGP Whitelist

This repo contains shared whitelist of PGP keys used in dependency verification by Wren Security projects.


## Creating Release

```
read -p "Enter new version: " VERSION
git tag -s $VERSION -m "Release $VERSION"
git push --tags
mvn deploy -Psign
```
