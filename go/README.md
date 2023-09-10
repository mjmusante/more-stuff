Go code should live here, but that doesn't currently work as Go modules can't be imported from a GitHub subdirectory. There's an accepted proposal to fix this (https://github.com/golang/go/issues/34055), so it should start working at some point — although the bug was reported in 2019 and the unimplemented proposal is from 2021, so it could take a while!

For now, I've moved the [Go code](../utf64.go) to the top level. The (currently) more "Go-like" solution would be to put all the Go code into its own repo, but I'd like to keep these implementations next to the [test.json](../test.json) spec.
