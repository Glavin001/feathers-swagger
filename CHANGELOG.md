# Change Log

## [NEXT]

**BREAKING:**
- swagger/openapi specifications have to be defined in `specs` instead of the root of the config object
- remove support of findQueryParameters option in favor of defaults with path support for nested structures
- default model names of versioned apis are now separated with _ instead of space which is necessary because of [\#109](https://github.com/feathersjs-ecosystem/feathers-swagger/issues/109)

**ADDED:**
- add option to ignore by paths
- add options to specify which services to include to documentation by paths or tags
- add appProperty option
- add docsJsonPath option
- add defaults option where generator functions or objects for customized defaults can be defined
- add possibility to use paths as keys for setting only parts of the specification
- add possibility to customize the refs used for different operations [\#116](https://github.com/feathersjs-ecosystem/feathers-swagger/issues/116)
- allow disabling of specific service methods [\#63](https://github.com/feathersjs-ecosystem/feathers-swagger/issues/63)
- add possibility to customize tag, tags and model for a service [\#24](https://github.com/feathersjs-ecosystem/feathers-swagger/issues/24) [\#112](https://github.com/feathersjs-ecosystem/feathers-swagger/issues/112)
- add support for OpenAPI v3 [\#137](https://github.com/feathersjs-ecosystem/feathers-swagger/issues/137) 

**FIXED:**
- do not use space in list ref [\#109](https://github.com/feathersjs-ecosystem/feathers-swagger/issues/109)

## [v0.7.3](https://github.com/feathersjs-ecosystem/feathers-swagger/tree/v0.7.3) (2019-04-15)
[Full Changelog](https://github.com/feathersjs-ecosystem/feathers-swagger/compare/v0.7.2...v0.7.3)

**Implemented enhancements:**

- chore: Standardise concatenation and object keys [\#131](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/131) ([EspadaV8](https://github.com/EspadaV8))

**Fixed bugs:**

- fix: Remove invalid securityDefinitions key from operations [\#133](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/133) ([EspadaV8](https://github.com/EspadaV8))

**Closed issues:**

- An in-range update of debug is breaking the build 🚨 [\#118](https://github.com/feathersjs-ecosystem/feathers-swagger/issues/118)
- Version 10 of node.js has been released [\#102](https://github.com/feathersjs-ecosystem/feathers-swagger/issues/102)
- Feature Idea: Validation [\#26](https://github.com/feathersjs-ecosystem/feathers-swagger/issues/26)

**Merged pull requests:**

- Add test to validate swagger specification, fix spec errors [\#139](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/139) ([Mairu](https://github.com/Mairu))
- Update mocha to the latest version 🚀 [\#134](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/134) ([greenkeeper[bot]](https://github.com/apps/greenkeeper))
- Update all dependencies [\#130](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/130) ([daffl](https://github.com/daffl))
- feat: Update list of nodejs versions to test against [\#129](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/129) ([EspadaV8](https://github.com/EspadaV8))
- fix: Remove invalid root level keys from swagger file [\#127](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/127) ([EspadaV8](https://github.com/EspadaV8))
- fix: Default security value should not be an object [\#126](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/126) ([EspadaV8](https://github.com/EspadaV8))
- Update feathers-sequelize to the latest version 🚀 [\#123](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/123) ([greenkeeper[bot]](https://github.com/apps/greenkeeper))
- Update semistandard to the latest version 🚀 [\#120](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/120) ([greenkeeper[bot]](https://github.com/apps/greenkeeper))
- Update debug to the latest version 🚀 [\#119](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/119) ([greenkeeper[bot]](https://github.com/apps/greenkeeper))

## [v0.7.2](https://github.com/feathersjs-ecosystem/feathers-swagger/tree/v0.7.2) (2018-07-24)
[Full Changelog](https://github.com/feathersjs-ecosystem/feathers-swagger/compare/v0.7.1...v0.7.2)

**Closed issues:**

- Codeclimate links and badges in readme are dead [\#103](https://github.com/feathersjs-ecosystem/feathers-swagger/issues/103)

**Merged pull requests:**

- API key authentication bug fixed, no more "undefined" security object. [\#115](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/115) ([ivanmarjanovic](https://github.com/ivanmarjanovic))
- added findQueryParameters [\#114](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/114) ([xFuryMaxHD](https://github.com/xFuryMaxHD))

## [v0.7.1](https://github.com/feathersjs-ecosystem/feathers-swagger/tree/v0.7.1) (2018-06-04)
[Full Changelog](https://github.com/feathersjs-ecosystem/feathers-swagger/compare/v0.7.0...v0.7.1)

**Closed issues:**

- Log statement in the code: Remove it? [\#110](https://github.com/feathersjs-ecosystem/feathers-swagger/issues/110)

**Merged pull requests:**

- Removed ui integration log statement [\#111](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/111) ([andys8](https://github.com/andys8))
- fix\(documentation\): Codeclimate badges [\#105](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/105) ([andys8](https://github.com/andys8))

## [v0.7.0](https://github.com/feathersjs-ecosystem/feathers-swagger/tree/v0.7.0) (2018-05-29)
[Full Changelog](https://github.com/feathersjs-ecosystem/feathers-swagger/compare/v0.5.1...v0.7.0)

## [v0.5.1](https://github.com/feathersjs-ecosystem/feathers-swagger/tree/v0.5.1) (2018-05-29)
[Full Changelog](https://github.com/feathersjs-ecosystem/feathers-swagger/compare/v0.6.0...v0.5.1)

**Closed issues:**

- Swagger & Express [\#106](https://github.com/feathersjs-ecosystem/feathers-swagger/issues/106)
- exclude [\#96](https://github.com/feathersjs-ecosystem/feathers-swagger/issues/96)
- Resolve Errors displayed in Swagger UI [\#91](https://github.com/feathersjs-ecosystem/feathers-swagger/issues/91)
- Test [\#65](https://github.com/feathersjs-ecosystem/feathers-swagger/issues/65)

**Merged pull requests:**

- Config contains idType to set default for application [\#108](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/108) ([andys8](https://github.com/andys8))
- fix\(documentation\): Improved markdown highlighting [\#104](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/104) ([andys8](https://github.com/andys8))
-  fix\(documentation\): Array items reference [\#101](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/101) ([jraut](https://github.com/jraut))
- typo fix [\#95](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/95) ([sarkistlt](https://github.com/sarkistlt))
- Update mocha to the latest version 🚀 [\#92](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/92) ([greenkeeper[bot]](https://github.com/apps/greenkeeper))
- Update semistandard to the latest version 🚀 [\#88](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/88) ([greenkeeper[bot]](https://github.com/apps/greenkeeper))
- Update feathers-sequelize to the latest version 🚀 [\#87](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/87) ([greenkeeper[bot]](https://github.com/apps/greenkeeper))
- Update feathers-memory to the latest version 🚀 [\#86](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/86) ([greenkeeper[bot]](https://github.com/apps/greenkeeper))

## [v0.6.0](https://github.com/feathersjs-ecosystem/feathers-swagger/tree/v0.6.0) (2017-11-08)
[Full Changelog](https://github.com/feathersjs-ecosystem/feathers-swagger/compare/v0.5.0...v0.6.0)

**Closed issues:**

- Outdated provider signature w/ Buzzard [\#83](https://github.com/feathersjs-ecosystem/feathers-swagger/issues/83)
- Is there a version that works with OAS 2.0? [\#82](https://github.com/feathersjs-ecosystem/feathers-swagger/issues/82)
- Swagger 3.x compatible version [\#78](https://github.com/feathersjs-ecosystem/feathers-swagger/issues/78)
- Did it working with last swagger 3.0 [\#61](https://github.com/feathersjs-ecosystem/feathers-swagger/issues/61)
- \[How to\] add documentation for the /auth/xxx endpoints [\#54](https://github.com/feathersjs-ecosystem/feathers-swagger/issues/54)

**Merged pull requests:**

- Update to new plugin infrastructure and fix test and examples [\#85](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/85) ([daffl](https://github.com/daffl))
- Fix: Adding support for Buzzard provider syntax \(\#83\) [\#84](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/84) ([alexisabril](https://github.com/alexisabril))
- Update mocha to the latest version 🚀 [\#80](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/80) ([greenkeeper[bot]](https://github.com/apps/greenkeeper))
- Support for Swagger UI 3.x [\#79](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/79) ([kristianmandrup](https://github.com/kristianmandrup))
- Update debug to the latest version 🚀 [\#77](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/77) ([greenkeeper[bot]](https://github.com/apps/greenkeeper))
- adding another example to readme [\#75](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/75) ([paul42](https://github.com/paul42))
- add link and comment about what is being defined [\#74](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/74) ([jamesjnadeau](https://github.com/jamesjnadeau))

## [v0.5.0](https://github.com/feathersjs-ecosystem/feathers-swagger/tree/v0.5.0) (2017-06-08)
[Full Changelog](https://github.com/feathersjs-ecosystem/feathers-swagger/compare/v0.4.0...v0.5.0)

**Merged pull requests:**

- Update sequelize to the latest version 🚀 [\#71](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/71) ([greenkeeper[bot]](https://github.com/apps/greenkeeper))
- Fix: docs ignored when path already exists \#23 [\#69](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/69) ([psi-4ward](https://github.com/psi-4ward))
- Quality of life [\#68](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/68) ([christopherjbaker](https://github.com/christopherjbaker))
- Update chai to the latest version 🚀 [\#66](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/66) ([greenkeeper[bot]](https://github.com/apps/greenkeeper))
- Update feathers-sequelize to the latest version 🚀 [\#60](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/60) ([greenkeeper[bot]](https://github.com/apps/greenkeeper))

## [v0.4.0](https://github.com/feathersjs-ecosystem/feathers-swagger/tree/v0.4.0) (2017-04-26)
[Full Changelog](https://github.com/feathersjs-ecosystem/feathers-swagger/compare/v0.3.5...v0.4.0)

**Merged pull requests:**

- Don't add empty paths [\#58](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/58) ([cpsubrian](https://github.com/cpsubrian))
- Update semistandard to the latest version 🚀 [\#57](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/57) ([greenkeeper[bot]](https://github.com/apps/greenkeeper))
- Update dependencies to enable Greenkeeper 🌴 [\#56](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/56) ([greenkeeper[bot]](https://github.com/apps/greenkeeper))
- Allow each method of a service to define docs. [\#52](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/52) ([cpsubrian](https://github.com/cpsubrian))
- Fixes a couple defaults that should be objects, not arrays. [\#49](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/49) ([cpsubrian](https://github.com/cpsubrian))

## [v0.3.5](https://github.com/feathersjs-ecosystem/feathers-swagger/tree/v0.3.5) (2017-04-01)
[Full Changelog](https://github.com/feathersjs-ecosystem/feathers-swagger/compare/v0.3.4...v0.3.5)

**Merged pull requests:**

- Fix extra whitespace if no versionPrefix is passed in config. [\#48](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/48) ([cpsubrian](https://github.com/cpsubrian))
- Fix 'text/html' redirect not respecting mountpath [\#47](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/47) ([cpsubrian](https://github.com/cpsubrian))

## [v0.3.4](https://github.com/feathersjs-ecosystem/feathers-swagger/tree/v0.3.4) (2017-03-23)
[Full Changelog](https://github.com/feathersjs-ecosystem/feathers-swagger/compare/v0.3.3...v0.3.4)

**Closed issues:**

- Definition for prefixed routes [\#39](https://github.com/feathersjs-ecosystem/feathers-swagger/issues/39)

**Merged pull requests:**

- Added config option to support api prefixing and versioning \(fix \#39\) [\#41](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/41) ([sinedied](https://github.com/sinedied))

## [v0.3.3](https://github.com/feathersjs-ecosystem/feathers-swagger/tree/v0.3.3) (2017-03-15)
[Full Changelog](https://github.com/feathersjs-ecosystem/feathers-swagger/compare/v0.3.2...v0.3.3)

**Closed issues:**

- Use default swagger-ui? [\#38](https://github.com/feathersjs-ecosystem/feathers-swagger/issues/38)
- can i use custom swagger-ui? [\#32](https://github.com/feathersjs-ecosystem/feathers-swagger/issues/32)
- ENOENT: no such file or directory [\#31](https://github.com/feathersjs-ecosystem/feathers-swagger/issues/31)

**Merged pull requests:**

- Added option to display default Swagger UI \(closes \#38\) [\#40](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/40) ([sinedied](https://github.com/sinedied))
- Update feathers-authentication to version 1.0.2 🚀 [\#34](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/34) ([greenkeeperio-bot](https://github.com/greenkeeperio-bot))

## [v0.3.2](https://github.com/feathersjs-ecosystem/feathers-swagger/tree/v0.3.2) (2016-12-12)
[Full Changelog](https://github.com/feathersjs-ecosystem/feathers-swagger/compare/v0.3.1...v0.3.2)

**Merged pull requests:**

- Fix definition [\#27](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/27) ([daffl](https://github.com/daffl))

## [v0.3.1](https://github.com/feathersjs-ecosystem/feathers-swagger/tree/v0.3.1) (2016-11-23)
[Full Changelog](https://github.com/feathersjs-ecosystem/feathers-swagger/compare/v0.3.0...v0.3.1)

**Closed issues:**

- Example apps only work when run from root of repo [\#21](https://github.com/feathersjs-ecosystem/feathers-swagger/issues/21)
- Should redirect from /docs to /docs/ [\#20](https://github.com/feathersjs-ecosystem/feathers-swagger/issues/20)
- TypeError: Cannot read property 'name' of undefined [\#19](https://github.com/feathersjs-ecosystem/feathers-swagger/issues/19)

**Merged pull requests:**

- Redirect HTML page to always trailing slash and use require.resolve to find UI [\#22](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/22) ([daffl](https://github.com/daffl))

## [v0.3.0](https://github.com/feathersjs-ecosystem/feathers-swagger/tree/v0.3.0) (2016-11-22)
[Full Changelog](https://github.com/feathersjs-ecosystem/feathers-swagger/compare/v0.1.0...v0.3.0)

## [v0.1.0](https://github.com/feathersjs-ecosystem/feathers-swagger/tree/v0.1.0) (2016-11-22)
**Implemented enhancements:**

- Use swagger-node-express [\#5](https://github.com/feathersjs-ecosystem/feathers-swagger/issues/5)
- Parse documentation with Dox \(or similar\) [\#3](https://github.com/feathersjs-ecosystem/feathers-swagger/issues/3)
- Complete support for REST API [\#2](https://github.com/feathersjs-ecosystem/feathers-swagger/issues/2)

**Fixed bugs:**

- Remove bower\_components/ [\#4](https://github.com/feathersjs-ecosystem/feathers-swagger/issues/4)

**Closed issues:**

- Update npm version [\#16](https://github.com/feathersjs-ecosystem/feathers-swagger/issues/16)
- Problem with path.join [\#13](https://github.com/feathersjs-ecosystem/feathers-swagger/issues/13)
- Please Provide Documentation/Make Example More Accessible [\#11](https://github.com/feathersjs-ecosystem/feathers-swagger/issues/11)
- Documentation Doesn't Exist: What Boneheaded Thing Did I Do? [\#10](https://github.com/feathersjs-ecosystem/feathers-swagger/issues/10)
- Supported in Feathers 2? [\#9](https://github.com/feathersjs-ecosystem/feathers-swagger/issues/9)
- See Swagger API docs [\#1](https://github.com/feathersjs-ecosystem/feathers-swagger/issues/1)

**Merged pull requests:**

- Get plugin release ready [\#18](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/18) ([daffl](https://github.com/daffl))
- support authorization setting and separation of docsPath and basePath [\#17](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/17) ([daffl](https://github.com/daffl))
- fix path.join windows issue [\#14](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/14) ([superbarne](https://github.com/superbarne))
- upgrate swagger to 2.0 [\#12](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/12) ([lpreterite](https://github.com/lpreterite))
- Update README.md [\#8](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/8) ([derek-watson](https://github.com/derek-watson))
- Add config option to set extension of generated docs [\#7](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/7) ([c10h22](https://github.com/c10h22))
- Update to feathers 1.2.0 [\#6](https://github.com/feathersjs-ecosystem/feathers-swagger/pull/6) ([c10h22](https://github.com/c10h22))



\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*
