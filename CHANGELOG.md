# Versioning

The H3 core library adheres to [Semantic Versioning](http://semver.org/).
H3-Py has a `major.minor.patch` version scheme. The major and minor version
numbers of H3-Py are the major and minor version of the bound core library,
respectively. The patch version is incremented independently of the core
library.

We use [this changelog structure](http://keepachangelog.com/).

Because H3-Py is versioned in lockstep with the H3 core library, please
avoid adding features or APIs which do not map onto the
[H3 core API](https://uber.github.io/h3/#/documentation/api-reference/).


## [3.6.1] - **Unreleased**

- Switch to Cython wrapper implementation


## [3.4.3] - 2019-04-18

- Removed null values in k_ring_distances.
- Support on Windows Platform
- Fixed some install problems


## [3.4.2] - 2019-03-13

- Added h3_line support.


## [3.1.0] - 2018-09-06

### Added
- Added h3_distance function.

### Changed
- Updated the core library to v3.1.0.

## [3.0.0] - 2018-07-24

### Added
- First public release.

