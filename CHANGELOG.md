# Change Log for OXID eShop Codeception Modules

All notable changes to this project will be documented in this file.
The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [unreleased] - unreleased

### Added
- SelectTheme module

## [2.0.0] - 2021-07-06

### Added
- Added `codeception/module-filesystem` in `composer.json` file

### Removed
- Removed database encoding:
  - config_key from ``src/Codeception/Template/ModuleAcceptance/acceptance.suite.yml``
  - protected requiredFields in ``src/Module/Database.php``

### Changed
- Public method signatures in `Module\OxideshopModules`

## [1.6.0] - 2021-07-06

### Added
- Support array as translation directories list

### Changed
- InvalidResourceException is thrown if not existing translations directory is listed

## [1.5.0] - 2021-03-25

### Added
- Support of codeception v4

## [1.4.0] - 2020-11-10

### Added
- Add `shopId` parameter to `updateConfigInDatabase` method
- Add `updateConfigInDatabaseForShops` method as alias for multiple shop calls of `updateConfigInDatabase`
- Method:
    - `OxidEsales\Codeception\Module\OxideshopModules::uninstallModule`
    - `OxidEsales\Codeception\Module\Database::grabConfigValueFromDatabase`
    - `OxidEsales\Codeception\Module\Oxideshop::regenerateDatabaseViews`

## [1.3.0] - 2020-07-06

### Added
- Flow theme module
- Methods:
    - `Module\Oxideshop::seeAndClick`

### Deprecated
- Activate modules within oxideshop

## [1.2.0] - 2020-01-02

### Added
- Use declare(strict_types=1); in template files
- Screen shot url for failing tests

### Fix
- Fix bootstrap's template configuration with ^3.1 codeception version

### Removed
- Removed database encoding:
    - config_key from ``src/Codeception/Template/ModuleAcceptance/acceptance.suite.yml``
    - protected requiredFields in ``src/Module/Database.php``

## [1.1.0] -  2019-11-07

### Added
- Template for module tests initialization is added
- OxideshopAdmin module with admin frames selection actions
- OxideshopModules module with just the OXID module activation

### Fix
- Improved the waitForAjax method jQuery waiting condition to work with shortened and full jQuery calls

## [1.0.0] -  2019-07-26

### Added
- First version of the module introduced

<<<<<<< HEAD
[2.0.0]: https://github.com/OXID-eSales/codeception-modules/compare/v1.6.0...v2.0.0
=======
[1.7.0]: https://github.com/OXID-eSales/codeception-modules/compare/v1.6.0...b-6.3.x
>>>>>>> b-6.3.x
[1.6.0]: https://github.com/OXID-eSales/codeception-modules/compare/v1.5.0...v1.6.0
[1.5.0]: https://github.com/OXID-eSales/codeception-modules/compare/v1.4.0...v1.5.0
[1.4.0]: https://github.com/OXID-eSales/codeception-modules/compare/v1.3.0...v1.4.0
[1.3.0]: https://github.com/OXID-eSales/codeception-modules/compare/v1.2.0...v1.3.0
[1.2.0]: https://github.com/OXID-eSales/codeception-modules/compare/v1.1.0...v1.2.0
[1.1.0]: https://github.com/OXID-eSales/codeception-modules/compare/v1.0.0...v1.1.0
[1.0.0]: https://github.com/OXID-eSales/codeception-modules/compare/78f569ceafc73440b800553c2f78885292aeccf8..v1.0.0
