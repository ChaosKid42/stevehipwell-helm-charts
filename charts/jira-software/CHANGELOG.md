# Jira Software Changelog

> [!NOTE]
> All notable changes to this project will be documented in this file; the format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/) and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

<!--
### Added - For new features.
### Changed - For changes in existing functionality.
### Deprecated - For soon-to-be removed features.
### Removed - For now removed features.
### Fixed - For any bug fixes.
### Security - In case of vulnerabilities.
-->

## [UNRELEASED]

## [v5.12.6] - 2025-01-13

### Changed

- Updated the _PostgreSQL_ dependency ot come from an OCI registry.
- Switched to using the port name for ingress.

### Deprecated

- This chart has been deprecated as Jira Server is no longer a supported product. ([#1110](https://github.com/stevehipwell/helm-charts/pull/1110)) _@stevehipwell_

## [v5.12.5] - 2024-03-13

> [!IMPORTANT]
> _Jira_ [v9.12](https://confluence.atlassian.com/jirasoftware/jira-software-9-12-x-release-notes-1319575972.html) is the last LTS release that supports the _Jira Software_ licence.

### Changed

- Updated the _Jira Software_ OCI image to [v9.12.5](https://confluence.atlassian.com/jirasoftware/jira-software-9-12-x-release-notes-1319575972.html).

## [v5.12.4] - 2024-03-13

> [!IMPORTANT]
> _Jira_ [v9.12](https://confluence.atlassian.com/jirasoftware/jira-software-9-12-x-release-notes-1319575972.html) is the last LTS release that supports the _Jira Software_ licence.

### Added

- Added a call to `/shutdown-wait.sh` from the pre-stop lifecycle hook.

### Changed

- Updated the _Jira Software_ OCI image to [v9.12.4](https://confluence.atlassian.com/jirasoftware/jira-software-9-12-x-release-notes-1319575972.html).

## [v5.12.3] - 2024-02-12

> [!IMPORTANT]
> _Jira_ [v9.12](https://confluence.atlassian.com/jirasoftware/jira-software-9-12-x-release-notes-1319575972.html) is the last LTS release that supports the _Jira Software_ licence.

### Changed

- Updated the _Jira Software_ OCI image to [v9.12.3](https://confluence.atlassian.com/jirasoftware/jira-software-9-12-x-release-notes-1319575972.html).

## [v5.12.2] - 2024-02-06

> [!IMPORTANT]
> _Jira_ [v9.12](https://confluence.atlassian.com/jirasoftware/jira-software-9-12-x-release-notes-1319575972.html) is the last LTS release that supports the _Jira Software_ licence.

### Changed

- Updated the _Jira Software_ OCI image to [v9.12.2](https://confluence.atlassian.com/jirasoftware/jira-software-9-12-x-release-notes-1319575972.html).

## [v5.12.1] - 2024-02-06

> [!IMPORTANT]
> _Jira_ [v9.12](https://confluence.atlassian.com/jirasoftware/jira-software-9-12-x-release-notes-1319575972.html) is the last LTS release that supports the _Jira Software_ licence.

### Changed

- Updated the _Jira Software_ OCI image to [v9.12.1](https://confluence.atlassian.com/jirasoftware/jira-software-9-12-x-release-notes-1319575972.html).

## [v5.12.0] - 2023-11-30

> [!IMPORTANT]
> _Jira_ [v9.12](https://confluence.atlassian.com/jirasoftware/jira-software-9-12-x-release-notes-1319575972.html) is the last LTS release that supports the _Jira Software_ licence.

### Changed

- Updated the _Jira Software_ OCI image to [v9.12.0](https://confluence.atlassian.com/jirasoftware/jira-software-9-12-x-release-notes-1319575972.html).

## [v5.11.4] - 2023-11-10

### Changed

- Updated the _Jira Software_ OCI image to [v9.11.3](https://confluence.atlassian.com/jirasoftware/jira-software-9-11-x-release-notes-1272283668.html).

## [v5.11.3] - 2023-10-20

### Changed

- Updated the embedded _PostgreSQL_ chart to [v12.12.10](https://artifacthub.io/packages/helm/bitnami/postgresql/12.10.2) (PostgreSQL v15.4.0).

### Fixed

- Fixed incorrect _PostgreSQL_ sub chart template names.

## [v5.11.2] - 2023-10-06

### Changed

- Updated the _Jira Software_ OCI image to [v9.11.2](https://confluence.atlassian.com/jirasoftware/jira-software-9-11-x-release-notes-1272283668.html).

## [v5.11.1] - 2023-09-25

### Changed

- Updated the _Jira Software_ OCI image to [v9.11.1](https://confluence.atlassian.com/jirasoftware/jira-software-9-11-x-release-notes-1272283668.html).
- Updated the embedded _PostgreSQL_ chart to [v12.10.2](https://artifacthub.io/packages/helm/bitnami/postgresql/12.10.2) (PostgreSQL v15.4.0).

## [v5.11.0] - 2023-08-31

### Added

- Added support for deleting `StatefulSet` PVCs on deletion in Kubernetes v1.27 or newer via the `persistence.retainDeleted` value which defaults to `true` to match the existing behaviour.

### Changed

- Updated the _Jira Software_ OCI image to [v9.11.0](https://confluence.atlassian.com/jirasoftware/jira-software-9-11-x-release-notes-1272283668.html).
- Updated the embedded _PostgreSQL_ chart to [v12.10.0](https://artifacthub.io/packages/helm/bitnami/postgresql/12.10.0) (PostgreSQL v15.4.0).

## [v5.10.1] - 2023-08-03

### Changed

- Updated the _Jira Software_ OCI image to [v9.10.1](https://confluence.atlassian.com/jirasoftware/jira-software-9-10-x-release-notes-1255446432.html).

## [v5.10.0] - 2023-07-11

### Changed

- Updated the _Jira Software_ OCI image to [v9.10.0](https://confluence.atlassian.com/jirasoftware/jira-software-9-10-x-release-notes-1255446432.html).

## [v5.9.1] - 2023-06-29

### Changed

- Updated the _Jira Software_ OCI image to [v9.9.1](https://confluence.atlassian.com/jirasoftware/jira-software-9-9-x-release-notes-1236934945.html).

## [v5.9.0] - 2023-06-05

### Changed

- Updated the _Jira Software_ OCI image to [v9.9.0](https://confluence.atlassian.com/jirasoftware/jira-software-9-9-x-release-notes-1236934945.html).

## [v5.8.1] - 2023-05-12

### All Changes

- Updated the _Jira Software_ image to [v9.8.1](https://confluence.atlassian.com/jirasoftware/jira-software-9-8-x-release-notes-1224776099.html).

## [v5.8.0] - 2023-04-25

### All Changes

- Updated the _Jira Software_ image to [v9.8.0](https://confluence.atlassian.com/jirasoftware/jira-software-9-8-x-release-notes-1224776099.html).

## [v5.7.1] - 2023-04-14

### All Changes

- Updated the _Jira Software_ image to [v9.7.1](https://confluence.atlassian.com/jirasoftware/jira-software-9-7-x-release-notes-1217298752.html).

## [v5.7.0] - 2023-03-24

### All Changes

- Updated the _Jira Software_ image to [v9.7.0](https://confluence.atlassian.com/jirasoftware/jira-software-9-7-x-release-notes-1217298752.html).
- Added support for `topologySpreadConstraints` with a default `labelSelector` for the release pods.
- Added a default `labelSelector` for the release pods to `affinity.podAffinity` & `affinity.podAntiAffinity`.

## [v5.6.0] - 2023-01-25

### All Changes

- Updated the _Jira Software_ image to [v9.6.0](https://confluence.atlassian.com/jirasoftware/jira-software-9-6-x-release-notes-1207174461.html).

## [v5.5.1] - 2023-01-20

### All Changes

- Updated the _Jira Software_ image to [v9.5.1](https://confluence.atlassian.com/jirasoftware/jira-software-9-5-x-release-notes-1188764867.html).

## [v5.5.0] - 2022-12-07

### All Changes

- Updated the _Jira Software_ image to [v9.5.0](https://confluence.atlassian.com/jirasoftware/jira-software-9-5-x-release-notes-1188764867.html).

## [v5.4.0] - 2022-11-15

### All Changes

- Updated the _Jira Software_ image to [v9.4.0](https://confluence.atlassian.com/jirasoftware/jira-software-9-4-x-release-notes-1178869757.html).
- Updated the embedded _PostgreSQL_ chart to [v11.9.13](https://artifacthub.io/packages/helm/bitnami/postgresql/11.9.13) (PostgreSQL v14.5.0).

## [v5.3.1] - 2022-10-25

### All Changes

- Updated the _Jira Software_ image to [v9.3.1](https://confluence.atlassian.com/jirasoftware/jira-software-9-3-x-release-notes-1168850570.html).

## [v5.3.0] - 2022-10-03

### All Changes

- Updated the _Jira Software_ image to [v9.3.0](https://confluence.atlassian.com/jirasoftware/jira-software-9-3-x-release-notes-1168850570.html).
- Updated the embedded _PostgreSQL_ chart to [v11.9.6](https://artifacthub.io/packages/helm/bitnami/postgresql/11.9.6) (PostgreSQL v14.5.0).

## [v5.2.0] - 2022-08-31

### Changed

- Updated _Jira Software_ image to [v9.2.0](https://confluence.atlassian.com/jirasoftware/jira-software-9-2-x-release-notes-1163763245.html).
- Updated embedded _PostgreSQL_ chart to [v11.8.1](https://artifacthub.io/packages/helm/bitnami/postgresql/11.8.1) (PostgreSQL v14.5.0).

## [v5.1.2] - 2022-08-26

### Changed

- Updated _Jira Software_ image to [v9.1.1](https://confluence.atlassian.com/jirasoftware/jira-software-9-1-x-release-notes-1142452845.html).

## [v5.1.1] - 2022-07-22

### Changed

- Fixed missing documentation for `deployment` value.

## [v5.1.0] - 2022-07-22

### Changed

- Update _Jira Software_ image to [v9.1.0](https://confluence.atlassian.com/jirasoftware/jira-software-9-1-x-release-notes-1142452845.html).
- Update embedded _PostgreSQL_ chart to [v11.6.18](https://artifacthub.io/packages/helm/bitnami/postgresql/11.6.18) (PostgreSQL v14.4.0).

## [v5.0.0] - 2022-06-21

> [!CAUTION]
> **BREAKING CHANGE** - If you're upgrading to this version you need to set `deployment` to `true` otherwise you might loose your data.

### Added

- Added new default behaviour to use a `StatefulSet` instead of a `Deployment`, the legacy behaviour can be enabled by setting `deployment` to `true`.
- Added `imagePullSecrets` to replace `image.pullSecrets`.
- Added `commonLabels` to allow the addition of labels to all resources.
- Added `terminationGracePeriodSeconds`.
- Added `service.clusterIP` to enable making the `Service` headless.
- Added `serviceAccount.automountToken` to default token binding to `false`.
- Added explicit namespace declaration in templates.
- Added support for setting `JVM_RESERVED_CODE_CACHE_SIZE` via `envVars.jvmReservedCodeCacheSize`.
- Added support for setting `ATL_FORCE_CFG_UPDATE` via `envVars.forceCfgUpdate`.
- Added support for setting `SET_PERMISSIONS` via `envVars.setPermissions`.

### Changed

- Update _Jira Software_ image to [v9.0.0](https://confluence.atlassian.com/jirasoftware/jira-software-9-0-x-release-notes-1142227613.html).
- Default to setting pod `fsGroup` to `2001`.
- Changed default JVM min heap size to the [default value](https://bitbucket.org/atlassian-docker/docker-atlassian-jira/src/master/#markdown-header-memory-heap-size) of `384M`.

### Removed

- Removed `image.pullSecrets` in favour of `imagePullSecrets`.

## [v4.10.3] - 2022-05-26

### Changed

- Update _Jira Software_ image to [v8.22.3](https://confluence.atlassian.com/jirasoftware/jira-software-8-22-x-release-notes-1115656979.html).

## [v4.10.2] - 2022-04-21

### Changed

- Update _Jira Software_ image to [v8.22.2](https://confluence.atlassian.com/jirasoftware/jira-software-8-22-x-release-notes-1115656979.html).

## [v4.10.1] - 2022-03-17

### Changed

- Update _Jira Software_ image to [v8.22.1](https://confluence.atlassian.com/jirasoftware/jira-software-8-22-x-release-notes-1115656979.html).

## [v4.10.0] - 2022-02-17

### Changed

- Update _Jira Software_ image to [v8.22.0](https://confluence.atlassian.com/jirasoftware/jira-software-8-22-x-release-notes-1115656979.html).
- Update embedded _PostgreSQL_ chart to [v10.16.2](https://artifacthub.io/packages/helm/bitnami/postgresql/10.16.2) (PostgreSQL v11.14.0).

## [v4.9.1] - 2022-01-31

### Changed

- Update _Jira Software_ image to [v8.21.1](https://confluence.atlassian.com/jirasoftware/jira-software-8-21-x-release-notes-1095249705.html).

## [v4.9.0] - 2021-12-11

### Changed

- Update _Jira Software_ image to [v8.21.0](https://confluence.atlassian.com/jirasoftware/jira-software-8-21-x-release-notes-1095249705.html).

## [v4.8.2] - 2021-11-18

### Changed

- Update _Jira Software_ image to [v8.20.2](https://confluence.atlassian.com/jirasoftware/jira-software-8-20-x-release-notes-1086411771.html).

## [v4.8.1] - 2021-11-01

### Changed

- Update _Jira Software_ image to [v8.20.1](https://confluence.atlassian.com/jirasoftware/jira-software-8-20-x-release-notes-1086411771.html).

## [v4.8.0] - 2021-10-21

### Changed

- Update _Jira Software_ image to [v8.20.0](https://confluence.atlassian.com/jirasoftware/jira-software-8-20-x-release-notes-1086411771.html).
- Update embedded _PostgreSQL_ chart to [v10.12.6](https://artifacthub.io/packages/helm/bitnami/postgresql/10.12.6) (PostgreSQL v11.13.0).

## [4.7.1] - 2021-09-16

### Changed

- Update _Jira Software_ image to [v8.19.1](https://confluence.atlassian.com/jirasoftware/jira-software-8-19-x-release-notes-1082526044.html).
- Update embedded _PostgreSQL_ chart to [v10.9.6](https://artifacthub.io/packages/helm/bitnami/postgresql/10.9.6) (PostgreSQL v11.13.0).

## [4.7.0] - 2021-08-27

### Changed

- Update _Jira Software_ image to [v8.19.0](https://confluence.atlassian.com/jirasoftware/jira-software-8-19-x-release-notes-1082526044.html).
- Update embedded _PostgreSQL_ chart to [v10.9.4](https://artifacthub.io/packages/helm/bitnami/postgresql/10.9.4) (PostgreSQL v11.13.0).

## [4.6.2] - 2021-08-26

### Removed

- Defective templating for `extraInitContainers`.

## v4.6.1 - 2021-08-19

### Changed

- Update _Jira Software_ image to [v8.18.2](https://confluence.atlassian.com/jirasoftware/jira-software-8-18-x-release-notes-1064094444.html).

## v4.6.0 - 2021-08-11

### Added

- Pod labels via `podlabels`.
- Extra volumes via `extraVolumes` and mounts for the _jira_ container via `extraVolumeMounts`.
- Extra init containers via `extraInitContainers`, which can be templated.

## v4.5.2 - 2021-07-23

### Changed

- Update _Jira Software_ image to [v8.18.1](https://confluence.atlassian.com/jirasoftware/jira-software-8-18-x-release-notes-1064094444.html)

## v4.5.1 - 2021-07-02

> [!NOTE]
> Republished chart.

### Changed

- Update _Jira Software_ image to [v8.18.0](https://confluence.atlassian.com/jirasoftware/jira-software-8-18-x-release-notes-1064094444.html)

## v4.5.0 - 2021-07-02

### Changed

- Update _Jira Software_ image to [v8.18.0](https://confluence.atlassian.com/jirasoftware/jira-software-8-18-x-release-notes-1064094444.html)

## v4.4.4 - 2021-06-28

### Changed

- Modify liveness probe to use TCP socket

## v4.4.3 - 2021-06-23

### Changed

- Fix ingress template

## v4.4.2 - 2021-06-21

### Changed

- Support K8s v1.18 ingress changes
- Fixed _PostgreSQL_ support

### Removed

- Customisable ingress path (not actually supported)

## v4.4.1 - 2021-06-16

### Changed

- Upgraded _Jira_ image to `v8.17.1`

## v4.4.0 - 2021-05-19

### Changed

- Upgraded _Jira_ image to `v8.17.0`

## v4.3.1 - 2021-04-20

### Changed

- Upgraded _Jira_ image to _v8.16.1_

## v4.3.0 - 2021-04-16

### Changed

- Default to JDK 11 image
- Upgraded _PostgreSQL_ chart to `v10.3.17` (_PostgreSQL_ `v11.11.0`)

## v4.2.0 - 2021-03-24

### Changed

- Upgraded _Jira_ image to _v8.16.0_

## v4.1.1 - 2021-02-16

### Changed

- Update default JVM config

## v4.1.0 - 2021-02-02

### Changed

- Upgraded _Jira_ image to _v8.15.0_

## v4.0.2 - 2021-01-15

### Added

- Dynamic probe configuration

## v4.0.1 - 2021-01-15

### Changed

- Upgraded _Jira_ image to _v8.14.1_

## v4.0.0 - 2021-01-06

> [!IMPORTANT]
> This release is only compatible with _Helm_ v3.

### Added

- New `priorityClassName` value

### Changed

- Upgraded chart API version to `v2`

## v3.3.0 - 2020-11-19

### Changed

- Upgrade image to _v8.14.0_

## v3.2.0 - 2020-11-03

### Changed

- Upgrade image to _v8.13.1_
- Use `.Chart.AppVersion` for default tag value

## v3.2.0 - 2020-10-08

### Changed

- Upgrade image to _v8.13.0_

## v3.1.3 - 2020-10-07

### Changed

- Upgrade image to _v8.12.3_

## v3.1.2 - 2020-09-22

### Changed

- Upgrade image to _v8.12.2_

## v3.1.1 - 2020-09-08

### Changed

- Upgrade image to _v8.12.1_

## v3.1.0 - 2020-08-28

### Changed

- Upgrade image to _v8.12.0_

## v3.0.1 - 2020-08-19

### Changed

- Upgrade image to _v8.11.1_

## v3.0.0 - 2020-08-05

### Changed

- Refactor chart
- Upgrade image to _v8.11.0_

<!--
RELEASE LINKS
-->
[UNRELEASED]: https://github.com/stevehipwell/helm-charts/tree/main/charts/jira-software
[v5.12.6]: https://github.com/stevehipwell/helm-charts/releases/tag/jira-software-5.12.6
[v5.12.5]: https://github.com/stevehipwell/helm-charts/releases/tag/jira-software-5.12.5
[v5.12.4]: https://github.com/stevehipwell/helm-charts/releases/tag/jira-software-5.12.4
[v5.12.3]: https://github.com/stevehipwell/helm-charts/releases/tag/jira-software-5.12.3
[v5.12.2]: https://github.com/stevehipwell/helm-charts/releases/tag/jira-software-5.12.2
[v5.12.1]: https://github.com/stevehipwell/helm-charts/releases/tag/jira-software-5.12.1
[v5.12.0]: https://github.com/stevehipwell/helm-charts/releases/tag/jira-software-5.12.0
[v5.11.4]: https://github.com/stevehipwell/helm-charts/releases/tag/jira-software-5.11.4
[v5.11.3]: https://github.com/stevehipwell/helm-charts/releases/tag/jira-software-5.11.3
[v5.11.2]: https://github.com/stevehipwell/helm-charts/releases/tag/jira-software-5.11.2
[v5.11.1]: https://github.com/stevehipwell/helm-charts/releases/tag/jira-software-5.11.1
[v5.11.0]: https://github.com/stevehipwell/helm-charts/releases/tag/jira-software-5.11.0
