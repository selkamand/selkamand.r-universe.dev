# universe

Repo listing packages to include in a personal cran-like repository (r_universe).

See [**selkamand packages**](https://selkamand.r-universe.dev/ui#builds)

For details on how to set up your own universe, see this [technical note](https://ropensci.org/blog/2021/06/22/setup-runiverse/)

To add your packages to the CCICB 'r-universe', simply add the package name and url to packages.json.

I Would also reccomend adding `![r-universe](https://selkamand.r-universe.dev/badges/PACKAGE_NAME)` to the top of your github README files to monitor build status.


To check on how your builds are progressing, see https://github.com/r-universe/selkamand/actions

To install a package from the CCICB universe, run:

```
install.packages("package_name", repos = "https://ropensci.r-universe.dev")
