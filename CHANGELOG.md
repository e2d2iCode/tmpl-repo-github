<!-- markdownlint-disable MD024 -->
# Changelog

All notable changes to this project will be documented in this file.

!!!Hint Conventions
    This document's format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
    and [Semantic Versionning](https://semver.org/spec/v2.0.0.htmlspec/v2.0.0.html).

<!--
--------------------------------------------------------------------------------
___  TEMPLATE     ______________________________________________________________
--------------------------------------------------------------------------------

SECTIONS
´´´´´´´´
## [Unreleased](https://github.com/e2d2iCode/tmpl-E2d2iApp-repo/compare/...HEAD)
## [<vers>](https://github.com/e2d2iCode/tmpl-E2d2iApp-repo/releases/tag/<the-tag>) &nbsp;-&nbsp; <yyy-mm-dd>
## [<vers>](https://github.com/e2d2iCode/tmpl-E2d2iApp-repo/compare/<to-that>...<this>) &nbsp;-&nbsp; <yyy-mm-dd>

### Added

- ...

### Changed

- ...

### Deprecated

- ...

### Removed

- ...

### Fixed

- ...

### Security

- ...

-----------------------------------------------------------------------------

MILESTONES
´´´´´´´´´

**[d<X.Y>-<label>-<Z>](https://github.com/e2d2iCode/tmpl-E2d2iApp-repo/compare/d<X.Y>-<label>-<N>...<base-tag>**

-->
<!--
--------------------------------------------------------------------------------
___ CHANGELOG   ________________________________________________________________
--------------------------------------------------------------------------------

NEW  VERSION  CHECKLIST  (!!! Release Branch !!!)
´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´´
The first 3 steps below should be taken eright on the `develop` branch, right before  the `telease` branch is created. If done on the `release` branch, then the changes should be merged back to the `develop` branch asap (before  its changelog is updated with new entries, otherwise tconflicts will occur when the `release` branch is merged back to the `develop` branch).

    [   ]  REPLACE [Unreleased] by the last release's next version

    [   ]  ADD today's date in the format YYYY-MM-DD

    [   ]  REPLACE [Unreleased] by the last release's next version

The step below finalizes the release's changelog. It should be the last commit on the `release` branch before the final merge happens.

    [   ]  MODIFY the comparison settings from `...HEAD` to `<to-that>...<this>`
-->

## [Unreleased](https://github.com/e2d2iCode/tmpl-E2d2iApp-repo/compare/...HEAD)

### Added

- ...

### Changed

- ...

### Deprecated

- ...

### Removed

- ...

### Fixed

- ...

### Security

- ...

---

## [Seed](https://github.com/e2d2iCode/tmpl-E2d2iApp-repo/releases/tag/v0.0.1) &nbsp;-&nbsp; 2025-06-01

### Added

- The standard seeding files:
  - .gitignore
  - README.md
  - LICENSE.md
