# Knot.x Releases
All notable changes to Knot.x will be documented in this file.

## Unreleased
List of changes that are finished but not yet released in any final version.
 - [PR-345](https://github.com/Cognifide/knotx/pull/345) - Update to Vert.x 3.5 and RxJava 2
 - [PR-320](https://github.com/Cognifide/knotx/pull/320) - Added KnotxServer configuration parameter to configure fileUploads folder

## Version 1.1.2
 - [PR-318](https://github.com/Cognifide/knotx/pull/318) - Knot.x returns exit code `30` in case of missing config
 - [PR-332](https://github.com/Cognifide/knotx/pull/332) - Fixed timeout issues when deploying verticles in Junit Rule
 - [PR-335](https://github.com/Cognifide/knotx/pull/335) - Added support for HttpServerOptions on the configuration level.
 - [PR-328](https://github.com/Cognifide/knotx/pull/328) - Knot.x ignore config parts related to not existing modules and allows to start the instance with warnings
 
## Version 1.1.1
 - [PR-316](https://github.com/Cognifide/knotx/pull/316) - Gateway Processor has access to request body
 - [PR-307](https://github.com/Cognifide/knotx/pull/307) - Fixed KnotxServer default configuration

## Version 1.1.0
 - [PR-293](https://github.com/Cognifide/knotx/pull/293) - Use vert.x WebClient and RxJava Single
 - [PR-294](https://github.com/Cognifide/knotx/pull/294) - Replace deprecated rx methods
 - [PR-295](https://github.com/Cognifide/knotx/pull/295) - Javadocs for core classes
 - [PR-296](https://github.com/Cognifide/knotx/pull/296) - Support for params on markup and config
 - [PR-299](https://github.com/Cognifide/knotx/pull/299) - Customize request routing outside knots
 - [PR-300](https://github.com/Cognifide/knotx/pull/300) - Change the default configuration for tests execution
 - [PR-306](https://github.com/Cognifide/knotx/pull/306) - Additional parameters to adapter from template

## Version 1.0.1
- [PR-288](https://github.com/Cognifide/knotx/pull/288) - action knot refactor
- [PR-290](https://github.com/Cognifide/knotx/pull/290) - allow defining services without default `params` configured
- [PR-289](https://github.com/Cognifide/knotx/pull/289) - upgraded versions: Vert.x to 3.4.1 and RxJava to 1.2.7
- [PR-285](https://github.com/Cognifide/knotx/pull/285) - fixed handling of Multiple headers with the same name
- [PR-278](https://github.com/Cognifide/knotx/pull/278) - fixed closing files in Filesystem Repository

## Version 1.0.0
- Initial open source release.
