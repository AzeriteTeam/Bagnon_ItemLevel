# Bagnon_ItemLevel Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/) 
and this project adheres to [Semantic Versioning](http://semver.org/).

## [1.0.10] 2018-1-20
### Changed
- The item level of Common (white) quality items like starter zone vendor gear and beginner Fishing Poles are now also displayed.

## [1.0.9] 2017-12-21
### Fixed
- Changed how artifacts and relics are scanned in WoW patch 7.3.0. Finally shows the upgraded crucible item levels! 

## [1.0.8] 2017-09-14
### Changed
- Slight code optimization, even less existence checks.

## [1.0.7] 2017-09-07
### Changed
- Optimized the code, reduced number of existence checks.

## [1.0.6] 2017-09-05
### Changed
- Moved the upgrade arrow used by Pawn yet again, to make it compatible with both this and the Bagnon_BoE addon.
- Changed the item level fontstring to use a common frame for all my bagnon plugins as a parent, to reduce number of extra frames.

## [1.0.5] 2017-09-04
### Changed
- Moved the upgrade arrow used by Pawn farther down so it wouldn't collide with the item level display.

## [1.0.4] 2017-09-03
### Changed
- Now does an extra check to get the effective item level for upgraded items.

## [1.0.3] 2017-08-29
### Changed
- Bumped the toc version to patch 7.3.0.

## [1.0.2] 2017-08-16
### Fixed
- Fixed the nil bug that prevented the addon from working. Thanks for fixing my "too little sleep" bugs, Kkhtnx! :) 

## [1.0.1] 2017-08-16
- Initial commit.