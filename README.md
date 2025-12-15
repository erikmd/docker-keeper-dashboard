# docker-keeper dashboard

[![google/go-containerregistry](https://img.shields.io/badge/ggcr-registry_explorer-green)](https://explore.ggcr.dev)

[![last upstream push](https://img.shields.io/github/last-commit/debuerreotype/docker-debian-artifacts/dist-amd64?path=bookworm%2Fslim%2FDockerfile&display_timestamp=committer&label=last%20upstream%20push)](https://github.com/debuerreotype/docker-debian-artifacts/blob/dist-amd64/bookworm/slim/Dockerfile)
[![debian image version](https://img.shields.io/docker/v/_/debian%2Fbookworm-slim?sort=semver&label=debian%20image%20version)](https://hub.docker.com/_/debian/tags?page=&page_size=&ordering=last_updated&name=bookworm-slim)

[![GitHub Release](https://img.shields.io/github/v/release/ocaml/opam?label=opam%20--version)](https://github.com/ocaml/opam/releases)
[![GitHub Release](https://img.shields.io/github/v/release/ocaml/dune?label=dune%20--version)](https://github.com/ocaml/dune/releases)

[![tags](https://img.shields.io/badge/tags%20on-docker%20hub-blue.svg)](https://hub.docker.com/r/rocq/base#supported-tags "Supported tags on Docker Hub")
[![pipeline status](https://gitlab.com/rocq-community/docker-base/badges/master/pipeline.svg)](https://gitlab.com/rocq-community/docker-base/-/pipelines)
[![dockerfile](https://img.shields.io/badge/docker--base%20on-github-blue.svg)](https://github.com/rocq-community/docker-base "Dockerfile source repository")
[![GitHub Issues](https://img.shields.io/github/issues/rocq-community/docker-base)](https://github.com/rocq-community/docker-base/issues)
[![GitHub PRs](https://img.shields.io/github/issues-pr/rocq-community/docker-base)](https://github.com/rocq-community/docker-base/pulls)

[![tags](https://img.shields.io/badge/tags%20on-docker%20hub-blue.svg)](https://hub.docker.com/r/coqorg/coq#supported-tags "Supported tags on Docker Hub")
[![pipeline status](https://gitlab.com/coq-community/docker-coq/badges/master/pipeline.svg)](https://gitlab.com/coq-community/docker-coq/-/pipelines)
[![dockerfile](https://img.shields.io/badge/docker--coq%20on-github-blue.svg)](https://github.com/coq-community/docker-coq "Dockerfile source repository")
[![GitHub Issues](https://img.shields.io/github/issues/coq-community/docker-coq)](https://github.com/coq-community/docker-coq/issues)
[![GitHub PRs](https://img.shields.io/github/issues-pr/coq-community/docker-coq)](https://github.com/coq-community/docker-coq/pulls)

[![tags](https://img.shields.io/badge/tags%20on-docker%20hub-blue.svg)](https://hub.docker.com/r/rocq/rocq-prover#supported-tags "Supported tags on Docker Hub")
[![pipeline status](https://gitlab.com/rocq-community/docker-rocq/badges/master/pipeline.svg)](https://gitlab.com/rocq-community/docker-rocq/-/pipelines)
[![dockerfile](https://img.shields.io/badge/docker--rocq%20on-github-blue.svg)](https://github.com/rocq-community/docker-rocq "Dockerfile source repository")
[![GitHub Issues](https://img.shields.io/github/issues/rocq-community/docker-rocq)](https://github.com/rocq-community/docker-rocq/issues)
[![GitHub PRs](https://img.shields.io/github/issues-pr/rocq-community/docker-rocq)](https://github.com/rocq-community/docker-rocq/pulls)

[![tags](https://img.shields.io/badge/tags%20on-docker%20hub-blue.svg)](https://hub.docker.com/r/mathcomp/mathcomp#supported-tags "Supported tags on Docker Hub")
[![pipeline status](https://gitlab.inria.fr/math-comp/docker-mathcomp/badges/master/pipeline.svg)](https://gitlab.inria.fr/math-comp/docker-mathcomp/-/pipelines)
[![dockerfile](https://img.shields.io/badge/docker--mathcomp%20on-github-blue.svg)](https://github.com/math-comp/docker-mathcomp "Dockerfile source repository")
[![GitHub Issues](https://img.shields.io/github/issues/math-comp/docker-mathcomp)](https://github.com/math-comp/docker-mathcomp/issues)
[![GitHub PRs](https://img.shields.io/github/issues-pr/math-comp/docker-mathcomp)](https://github.com/math-comp/docker-mathcomp/pulls)

[![mathcomp-dev](https://img.shields.io/badge/tags%20on-docker%20hub-blue.svg)](https://hub.docker.com/r/mathcomp/mathcomp-dev "Images on Docker Hub")
[![pipeline status](https://gitlab.inria.fr/math-comp/math-comp/badges/master/pipeline.svg)](https://gitlab.inria.fr/math-comp/math-comp/-/pipelines)
[![dockerfile](https://img.shields.io/badge/mathcomp--dev%20on-github-blue.svg)](https://github.com/math-comp/math-comp "Dockerfile source repository")

[![Docker-Coq CI][docker-coq-ci-badge]][docker-coq-ci-link]
[![Docker-based CI][python-ci-badge]][python-ci-link]  
[![RT CI][rt-ci-badge]][rt-ci-link]
[![reviewdog][reviewdog-badge]][reviewdog-link]
[![github-action](https://img.shields.io/badge/docker--coq--action%20on-github-blue.svg)](https://github.com/coq-community/docker-coq-action "docker-coq-action repository")
[![GitHub Issues](https://img.shields.io/github/issues/coq-community/docker-coq-action)](https://github.com/coq-community/docker-coq-action/issues)
[![GitHub PRs](https://img.shields.io/github/issues-pr/coq-community/docker-coq-action)](https://github.com/coq-community/docker-coq-action/pulls)


[reviewdog-badge]: https://github.com/coq-community/docker-coq-action/actions/workflows/reviewdog.yml/badge.svg?branch=master
[reviewdog-link]:https://github.com/coq-community/docker-coq-action/actions/workflows/reviewdog.yml

[docker-coq-ci-badge]: https://github.com/coq-community/docker-coq-action/actions/workflows/coq-demo.yml/badge.svg?branch=master
[docker-coq-ci-link]:https://github.com/coq-community/docker-coq-action/actions/workflows/coq-demo.yml

[python-ci-badge]: https://github.com/coq-community/docker-coq-action/actions/workflows/python-demo.yml/badge.svg?branch=master
[python-ci-link]:https://github.com/coq-community/docker-coq-action/actions/workflows/python-demo.yml

[rt-ci-badge]: https://github.com/coq-community/docker-coq-action/actions/workflows/gha-rt.yml/badge.svg?branch=master
[rt-ci-link]:https://github.com/coq-community/docker-coq-action/actions/workflows/gha-rt.yml

[![subtree](https://img.shields.io/badge/docker--keeper%20on-gitlab-blue.svg)](https://gitlab.com/erikmd/docker-keeper "docker-keeper repository")
[![pipeline status](https://gitlab.com/erikmd/docker-keeper/badges/master/pipeline.svg)](https://gitlab.com/erikmd/docker-keeper/-/pipelines)
[![GitLab Issues](https://img.shields.io/gitlab/issues/open/erikmd%2Fdocker-keeper)](https://gitlab.com/erikmd/docker-keeper/-/issues)
[![GitLab MRs](https://img.shields.io/gitlab/merge-requests/open/erikmd%2Fdocker-keeper)](https://gitlab.com/erikmd/docker-keeper/-/merge_requests)
