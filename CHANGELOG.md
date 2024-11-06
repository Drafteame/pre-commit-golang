## v0.11.0 (2024-11-06)


- ci: fix version (#17)
- ci: replace to use commitizen action (#16)
- ci: fix python action (#15)
- feat: force mod version (#14)
- * feat: add force mod version hook

* docs: add new hook docs
- chore: sync from source
- bump: version 0.10.0 → 0.10.1
- fix: filter deleted staged files to revive hook (#12)
- bump: version 0.9.1 → 0.10.0
- feat: run revive only on staged files (#11)
- bump: version 0.9.0 → 0.9.1
- fix: add execution permissions to sh files (#10)
- bump: version 0.8.1 → 0.9.0
- feat: add hook to execute revive lint (#9)
- chore: add forward arguments to goimports-reviser hook (#8)
- bump: version 0.8.0 → 0.8.1
- fix: go vet hook exit code (#7)
- bump: version 0.7.0 → 0.8.0
- feat: add go vet hook (#6)
- bump: version 0.6.0 → 0.7.0
- fix: executable (#5)
- * fix: add execute permissions to new commands

* fix: commitizen configuration
- bump: version 0.5.2 → 0.6.0
- feat: add go imports reviser hook (#4)
- * feat: add go imports reviser hook

* fix: readme
- bump: version 0.5.1 → 0.5.2
- fix: go commands
- bump: version 0.5.0 → 0.5.1
- fix: readme docs
- bump: version 0.4.0 → 0.5.0
- feat: add .cz.toml file
- feat: adjust hooks to draftea style
- Merge pull request #97 from lightglitch/master
- Improving cross-platform support
- Improving cross-platform support
- Merge pull request #99 from dnephin/announcement
- Update README
- Update README
- Merge pull request #96 from j2gg0s/feat-allow-args
- feat(mod): allow user pass args
- feat(mod): allow user pass args
- Merge pull request #95 from OnePunMan/bug/go-unit-test-false-positive
- Fix go-unit-test script falsely succeeding if go list ./... fails
- fix go-unit-test script falsely succeeding if go list ./... fails
- Merge pull request #92 from burik666/go-generate
- Fix go-generate for multiple directories
- Fix go-generate for multiple directories
- Merge pull request #91 from Jarmos-san/master
- Update README with a deprecation notice for `golang/go-lint`
- Update README with a deprecation notice
- Merge pull request #88 from mckingho/patch-1
- Change shebang to bash in golangci-lint script
- Change shebang to bash in golangci-lint script
- Merge pull request #86 from dnephin/fix-command-check
- Fix command check
- Add some missing sets
- Some don't do anything now, but may in the future when things are added.
- Fix command check
- Merge pull request #85 from ccoVeille/error-reporting
- add error messages when the command expected is not available
- Update run-go-critic.sh
- add error messages when the command expected is not available
- this avoids silent issues that may let think that everything is ok

## v0.10.1 (2023-09-08)


- bump: version 0.10.0 → 0.10.1
- fix: filter deleted staged files to revive hook (#12)

## v0.10.0 (2023-09-06)


- bump: version 0.9.1 → 0.10.0
- feat: run revive only on staged files (#11)

## v0.9.1 (2023-08-29)


- bump: version 0.9.0 → 0.9.1
- fix: add execution permissions to sh files (#10)

## v0.9.0 (2023-08-29)


- bump: version 0.8.1 → 0.9.0
- feat: add hook to execute revive lint (#9)
- chore: add forward arguments to goimports-reviser hook (#8)

## v0.8.1 (2023-03-28)


- bump: version 0.8.0 → 0.8.1
- fix: go vet hook exit code (#7)

## v0.8.0 (2023-03-28)


- bump: version 0.7.0 → 0.8.0
- feat: add go vet hook (#6)

## v0.7.0 (2022-10-04)


- bump: version 0.6.0 → 0.7.0
- fix: executable (#5)
- * fix: add execute permissions to new commands

* fix: commitizen configuration
- bump: version 0.5.2 → 0.6.0
- feat: add go imports reviser hook (#4)
- * feat: add go imports reviser hook

* fix: readme
- bump: version 0.5.1 → 0.5.2
- fix: go commands
- bump: version 0.5.0 → 0.5.1
- fix: readme docs
- bump: version 0.4.0 → 0.5.0
- feat: add .cz.toml file
- feat: adjust hooks to draftea style
- Merge pull request #77 from giorgiop/switch2http
- Switch to https
- switch to https
- Merge pull request #73 from dtomasi/feature/add-go-generate
- feat: add script for go generate
- Update run-go-generate.sh
- Co-authored-by: Daniel Nephin <dnephin@gmail.com>
- feat: add script for go generate
- Merge pull request #70 from larsks/bug/61
- Remove gometalinter
- Deprecate gometalinter
- The gometalinter project was abandoned in 2019. This commit modifies
the run-gometalinter script to emit a deprecation message and fail.
- Closes #61
- Merge pull request #69 from naphatkrit/master
- add -o pipefail to gofmt and goimports scripts
- add -o pipefail to gofmt and goimports

## v0.4.0 (2020-11-21)


- Merge pull request #65 from callofdutyops/master
- support pre-commit exclude
- support pre-commit exclude
- Merge pull request #58 from logikone/go-mod-vendor
- feat: add go-mod-vendor hook
- feat: add go-mod-vendor hook
- * Add a hook that runs `go mod vendor` to ensure that vendored
dependencies are up-to-date
- Merge pull request #56 from echarrod/master
- Use `#!/usr/bin/env x` instead of `#!/bin/x` for compatibility with Windows
- Fix #54: go-cyclo - use `#!/usr/bin/env bash` instead of `#!/bin/bash` for compatibility with Windows
- Fix #55: golangci-lint - use `#!/usr/bin/env sh` instead of `#!/bin/sh` for compatibility with Windows
- Merge pull request #43 from Jerome1337/master
- Implement go mod tidy script
- Implement go mod tidy script
- Useful to check if:
- * Some packages are not required
* Some package needs to be updated
- Merge pull request #42 from ramonhpr/patch-1
- Add recursive files in go-build hook
- Add recursive files in go-build hook

## v0.3.5 (2019-10-14)


- Merge pull request #40 from Jerome1337/master
- Add gocyclo pre-commit hook
- Add gocyclo pre-commit hook
- Merge pull request #39 from gangachris/doc
- add doc for goimports
- add doc for goimports
- Merge pull request #37 from colinschoen/master
- Add go imports pre-commit hook
- Register go imports pre-commit hook
- Add goimports pre-commit hook
- Merge pull request #35 from kelda/master
- golangci-lint: fix invocation, skip vendor/, add --fix --fast --new
- golangci-lint: update invocation
- update the invocation of golangci-lint to not spawn multiple
redundant copies per cpu since it handles its own concurrency.
- also, by using "$@" users can pass their own arguments in their
repository's .pre-commit-config.yaml, e.g. to add `args: ['--fix',
'--fast', '--new']` to enable the fast linter preset, only run on
newly-modified files, and fix problems as they arise, if the linter
supports it

## v0.3.4 (2019-06-24)


- Merge pull request #34 from davidpfarrell/patch-1
- Update go-critic section in README.md
- Update go-critic section in README.md
- A recent PR ( #33 ) was merged, correcting the go-critic script.  This PR brings  README.md into alignment with.
- Merge pull request #33 from korjavin/go-critic
- Fix exec command for new go-critic release
- Use more "general" options
- Fix exec command for new go-critic release
- Merge pull request #29 from jonyhy96/master
- Fix issue #28
- Fix issue #28

## v0.3.3 (2019-03-09)


- Merge pull request #25 from michilu/fix/go-vet
- (fix) case of multiple go files in one directory
- fix case of multiple go files in one directory
- Merge pull request #24 from jasonfriedland/jfriedland/go-112-too-vet
- Use of "go tool vet" deprecated as of Go 1.12
- Use of "go tool vet" deprecated as of Go 1.12
- Merge pull request #21 from covertbert/master
- Adds a hook for go build
- Update README.md
- Adds README entries etc
- Adds go build hook yml reference
- Adds go build
- Merge pull request #20 from vallieres/add-documentation
- Added examples in the README
- Added examples in the README
- Merge pull request #19 from vallieres/master
- Added go-unit-tests
- Added go-unit-tests
- Added this one which will run all of the unit tests
- Merge pull request #18 from rumyantseva/master
- Make run-go-critic.sh executable
- Make run-go-critic.sh executable
- Merge pull request #17 from rumyantseva/master
- Added go-critic to the list of possible linters
- Added go-critic to the list of possible linters
- Merge pull request #16 from flw-cn/pr/fix-typo
- fix typo: gos' => go's
- Fix: typo
- gos' => go's
- Merge pull request #15 from flw-cn/feature/add-golangci-lint
- Feat: add golangci-lint
- Feat: add golangci-lint
- See also: https://github.com/golangci/golangci-lint
- Merge pull request #14 from asottile/patch-1
- Switch from `pcre` to `pygrep`
- Switch from `pcre` to `pygrep`
- The [`pygrep`](https://pre-commit.com/#pygrep) language was added in `pre-commit` 1.2.0 as a replacement for `pcre` (which is scheduled for removal in pre-commit 2.x).

In this case, it is a drop-in replacement

Resolves #8
- Add a License
- Fixes #13

## v0.3.2 (2018-03-27)


- Merge pull request #12 from jim/more-robust-go-lint
- Use -set_exit_status instead of capturing output. Fixes #10.
- Use -set_exit_status instead of capturing output. Fixes #10.

## v0.3.1 (2018-03-13)


- Merge pull request #9 from jim/explicit-exits
- Add explicit exit if any of the golint runs return non-zero.
- Add explicit exit if any of the golint runs return non-zero.
- Merge pull request #6 from akostibas/ak-fix-go-vet
- Run `go tool vet` against single files instead of `go vet`
- run `go tool vet` against single files, not `go vet`
- Merge pull request #3 from borisbabic/fix/hashbang
- Improve bash hashbang
- Improve bash hashbang
- Update readme.
- Signed-off-by: Daniel Nephin <dnephin@gmail.com>
- Add gometalinter.
- Signed-off-by: Daniel Nephin <dnephin@gmail.com>
- Update hooks version.
- Signed-off-by: Daniel Nephin <dnephin@gmail.com>
- Fixes #2 - Move hooks config to new location.
- Run lint on individual files.
- Add descriptions to hooks files.
- Update README.
- Add first draft of golang and related hooks.
- init
