# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

<a name="7.7.2"></a>
## [7.7.2](https://github.com/heroku/cli/compare/v7.7.1...v7.7.2) (2018-07-18)


### Bug Fixes

* **pipelines:** get archive_link from payload instead of body ([#946](https://github.com/heroku/cli/issues/946)) ([402d195](https://github.com/heroku/cli/commit/402d195))




<a name="7.7.1"></a>
## [7.7.1](https://github.com/heroku/cli/compare/v7.7.0...v7.7.1) (2018-07-17)


### Bug Fixes

* **pipelines:** change source_blob url to come from kolkrabbi ([#944](https://github.com/heroku/cli/issues/944)) ([2f50f07](https://github.com/heroku/cli/commit/2f50f07))




<a name="7.5.6"></a>
## [7.5.6](https://github.com/heroku/cli/compare/v7.5.5...v7.5.6) (2018-06-29)


### Bug Fixes

* bump legacy and color ([a3fa970](https://github.com/heroku/cli/commit/a3fa970))




<a name="7.5.5"></a>
## [7.5.5](https://github.com/heroku/cli/compare/v7.5.4...v7.5.5) (2018-06-29)




**Note:** Version bump only for package @heroku-cli/plugin-pipelines-v5

<a name="7.5.1"></a>
## [7.5.1](https://github.com/heroku/cli/compare/v7.5.0...v7.5.1) (2018-06-26)


### Bug Fixes

* bump dev-cli ([fb3e41a](https://github.com/heroku/cli/commit/fb3e41a))




<a name="7.5.0"></a>
# [7.5.0](https://github.com/heroku/cli/compare/v7.4.11...v7.5.0) (2018-06-26)




**Note:** Version bump only for package @heroku-cli/plugin-pipelines-v5

<a name="7.4.8"></a>
## [7.4.8](https://github.com/heroku/cli/compare/v7.4.7...v7.4.8) (2018-06-21)




**Note:** Version bump only for package @heroku-cli/plugin-pipelines-v5

<a name="7.4.6"></a>
## [7.4.6](https://github.com/heroku/cli/compare/v7.4.5...v7.4.6) (2018-06-20)


### Bug Fixes

* update dev-cli readme generation ([42a77bc](https://github.com/heroku/cli/commit/42a77bc))




<a name="7.4.5"></a>
## [7.4.5](https://github.com/heroku/cli/compare/v7.4.4...v7.4.5) (2018-06-20)


### Bug Fixes

* updated monorepo documentation urls ([4bb6fe0](https://github.com/heroku/cli/commit/4bb6fe0))




<a name="7.4.0"></a>
# [7.4.0](https://github.com/heroku/cli/compare/v7.3.0...v7.4.0) (2018-06-19)


### Bug Fixes

* repo name ([c306c78](https://github.com/heroku/cli/commit/c306c78))




Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## Unreleased

## [2.5.10] 2018-06-18

- Added help topic descriptions

## [2.5.9] 2018-05-14

- Updated validator to fix snyk vuln

## [2.5.8] 2018-04-26

- Re-add the `disambiguatePipeline` export

## [2.5.7] 2018-04-21

- Exclude tests files from tarball

## [2.5.6] 2018-04-20

- Re-released 2.5.4 to include oclif manifest

## [2.5.5] 2018-04-20

- Re-released 2.5.4 to include oclif manifest

## [2.5.4] 2018-04-18

- Switch to http-call from got
- Updated dependencies

## [2.5.3] 2018-03-26

- Added command `pipelines:connect` to connect an existing pipeline to a Github repo.
- Added command `reviewapps` to enable|disable review apps with an existing pipeline.
- Improves caching strategy and use new scope convention to declare this a core Heroku CLI plugin.

## [2.5.2] 2018-02-20

- Use oclif.io as a dependency.

## [2.5.1] 2018-02-13

- Fixes https://github.com/heroku/heroku-pipelines/issues/80.
- Removes requirement for CI flag (Heroku CI has been GA for some time). This fix actually allows everybody to configure their pipelines with Heroku CI now.
- Fixes an issue when not sending arguments in the `pipeline:setup` command.

## [2.5.0] 2017-11-20

- Update `pipelines:transfer` to perform a full transfer including apps in the pipeline.

## [2.4.0] 2017-10-11

- Add `pipelines:transfer` command to set and update the pipeline owner.

## [2.3.1] 2017-09-13

- Fixes serialization for `pipelines:info --json`. https://github.com/heroku/heroku-pipelines/pull/72 changed the serialization for that command changing `apps` to `pipelineApps`.

## [2.3.0] 2017-09-12

- Update help output of `pipelines:info`
- Show warning when operating in an owned pipeline with apps with different owners with the `pipelines:info` command.
- Add support for creating a pipeline with an owner. Uses the personal account as owner if no owner is specified via `--team` or `--org`
- Update `pipelines:setup` to use `--org` rather than `--organization` when creating a pipeline to an organization. This is to preserve consistency with other CLI commands.
- Add stage flag options completion

## [2.2.0] 2017-09-06

- Show pipeline owner when it has one set in the command `pipelines:info`
- Update the output format to use columns in `pipelines:info` so it's more machine readable (grep-parsable)
- Add support for hidden flag `--with-owners` to show app owner in all pipeline-couplings in `pipelines:info`


## [2.1.3] - 2017-06-30
### Changed
- Loosened dependencies
