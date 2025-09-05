# demo-core-repo

## common

Some common code used by the charm(s) in this repo.

## demo-one

Contains charm code and most metadata for this charm. Essentially empty charm with a placeholder config and action. To be packed with the uv plugin. Depends on the sibling directory `common` via a symlink (`demo-one/common` -> `../common`) for easy redirection in the `part` when packing.
