# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project is a plugin for [RaccoonBot Attack Algorithm](https://www.raccoonbot.com/forum/topic/24589-all-in-one-push-deploy/).

## [2.1.4.417](https://github.com/cobratst/GoblinKnifeDeployAddon/raw/master/AllInOnePushDeploy.2.1.4.417.zip). 07 july 2018
### Added:
- Suport for Electro Dragon.
- Force zoom out before attack.

## [2.0.7.415](https://github.com/cobratst/GoblinKnifeDeployAddon/raw/master/AllInOnePushDeploy_2.0.7.415.zip). - 31 OCT 2017
### Added:
- New Babyloon with clone support.
- add support for baby dragon funnelling with lavaloonion attacks.

## [2.0.7.413](https://github.com/cobratst/GoblinKnifeDeployAddon/raw/master/AllInOnePushDeploy_2.0.7.413.zip). - 12 OCT 2017
### Added:
- New option to use rage spells on funnelling troops.
- Clone spell support for air attacks.
- Debug screenshot if attack from bottom right side to analysis the new generated points.
- Option to avoid bottom right side if you have issues with it.
### Fixed:
- Bottom right side attacks is now available after generating our own deployment points.
- Second jump spell location is now based on better walls detection.
- Timing for deploying 2nd jump spell is now before clanCastle,heroes and normal troops.
### Changed:
- Wizard deployment if there is bowlers . will drop one on each funnelling side and the rest are for center.
- Air funnelling points is now from corners.
- Delay heroes deployment in air attacks to make sure funnell was created and they goto the core of the base.

## [2.0.7.408](https://github.com/cobratst/GoblinKnifeDeployAddon/raw/master/AllInonePushDeploy_2.0.7.408.zip). - 28 SEP 2017
### Fixed:
- Deploy Order if there are no giants.

## [2.0.7.406](https://github.com/cobratst/GoblinKnifeDeployAddon/raw/master/AllInonePushDeploy_2.0.7.406.zip). - 26 SEP 2017
### Fixed:
- issue with 2.0.7.404 jump spell deployed on EQ drop point.

## [2.0.7.402](https://github.com/cobratst/GoblinKnifeDeployAddon/raw/master/AllInOnPushDeploy_2.0.7.402.zip). - 11 SEP 2017
### Added:
- Shift spells positions to inside up to 5 tiles and to outside up to -5 tiles.
- Display list of used troops for debugging.
### Fixed:
- If EQ will overlap with jump spell we move it to inside to cover better erea.
- Red message after deploying second rage.
