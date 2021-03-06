# Change Log
All notable changes to this project will be documented in this file.
This project follows [Semantic Versioning](http://semver.org/).

## [Unreleased][unreleased]

## 0.5.0 - 2015-01-03
### Changed
- BC-break: all dates are now parsed as datetime objects

### Added
- Implementation for changeset discussions (ChangesetComment, ChangesetSubscribe, ChangesetUnsubscribe)
- When (un)subscribing to a changeset, there are two special errors `AlreadySubscribedApiError` and `NotSubscribedApiError` to check for
- The ChangesetGet method got a new parameter `include_discussion` to determine wheter or not changeset discussion should be in the response

## 0.4.2 - 2015-01-01
### Fixed
- Result of `NodeWay` is now actually parsed as a `way`

### Added
- Lots of method comments for documentation

### Changed
- Update to pdoc 0.3.1 which changed the appearance of the online docs

## 0.4.1 - 2014-10-08
### Changed
- Parse dates in notes as `datetime` objects

## 0.4.0 - 2014-10-07
### Added
- Release for OSM Notes API
- Generation of online documentation (http://osmapi.divshot.io)

## 0.3.1 - 2014-06-21
### Fixed
- Hotfix release of Python 3.x (base64)

## 0.3.0 - 2014-05-20
### Added
- Support for Python 3.x
- Use `tox` to run tests against multiple versions of Python

## 0.2.26 - 2014-05-02
### Fixed
- Fixed notes again

## 0.2.25 - 2014-05-02
### Fixed
- Unit tests for basic functionality
- Fixed based on the unit tests (previously undetected bugs)

## 0.2.24 - 2014-01-07
### Fixed
- Fixed notes

## 0.2.23 - 2014-01-03
### Changed
- Hotfix release

## 0.2.22 - 2014-01-03
### Fixed
- Fixed README.md not found error during installation

## 0.2.21 - 2014-01-03
### Changed
- Updated description

## 0.2.20 - 2014-01-01
### Added
- First release of PyPI package "osmapi"

## 0.2.19 - 2014-01-01
### Changed
- Inital version from SVN (http://svn.openstreetmap.org/applications/utils/python_lib/OsmApi/OsmApi.py)
- Move to GitHub

## 0.2.19 - 2010-05-24
### Changed
- Add debug message on ApiError

## 0.2.18 - 2010-04-20
### Fixed
- Fix ChangesetClose and _http_request

## 0.2.17 - 2010-01-02
### Added
- Capabilities implementation

## 0.2.16 - 2010-01-02
### Changed
- ChangesetsGet by Alexander Rampp

## 0.2.15 - 2009-12-16
### Fixed
- xml encoding error for < and >

## 0.2.14 - 2009-11-20
### Changed
- changesetautomulti parameter

## 0.2.13 - 2009-11-16
### Changed
- modify instead update for osc

## 0.2.12 - 2009-11-14
### Added
- raise ApiError on 4xx errors

## 0.2.11 - 2009-10-14
### Fixed
- unicode error on ChangesetUpload

## 0.2.10 - 2009-10-14
### Added
- RelationFullRecur definition

## 0.2.9  - 2009-10-13
### Added
- automatic changeset management
- ChangesetUpload implementation

## 0.2.8  - 2009-10-13
### Changed
- *(Create|Update|Delete) use not unique _do method

## 0.2.7  - 2009-10-09
### Added
- implement all missing functions except ChangesetsGet and GetCapabilities

## 0.2.6  - 2009-10-09
### Changed
- encoding clean-up

## 0.2.5  - 2009-10-09
### Added
- implements NodesGet, WaysGet, RelationsGet, ParseOsm, ParseOsc

## 0.2.4  - 2009-10-06 clean-up
### Changed
- clean-up

## 0.2.3  - 2009-09-09 
### Changed
- keep http connection alive for multiple request
- (Node|Way|Relation)Get return None when object have been deleted (raising error before)

## 0.2.2  - 2009-07-13
### Added
- can identify applications built on top of the lib

## 0.2.1  - 2009-05-05
### Changed
- some changes in constructor

## 0.2    - 2009-05-01
### Added
- initial import


# Categories
- `Added` for new features.
- `Changed` for changes in existing functionality.
- `Deprecated` for once-stable features removed in upcoming releases.
- `Removed` for deprecated features removed in this release.
- `Fixed` for any bug fixes.
- `Security` to invite users to upgrade in case of vulnerabilities.
