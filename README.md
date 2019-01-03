# ETS Poms

[![Build Status](https://travis-ci.org/Galeria-Kaufhof/ets-poms.svg?branch=master)](https://travis-ci.org/Galeria-Kaufhof/ets-poms)
[![Gitter chat](https://badges.gitter.im/gitterHQ/gitter.png)](https://gitter.im/Galeria-Kaufhof/ETS)

This project contains all POMs defining a ETS release.

## Changelog

### 0.6.0
- Add `src/main/dev-resources` as resources directory for all ets-applications
### 0.5.0
- Force scala compiler to use the `ets.java.version`
### 0.4.0
- Add Maven assembly descriptor for application
- Activate plugins and add dependencies depending on profiles
### 0.3.0
- Update scala-maven-plugin to 3.4.1
- Add akka-http-spray-json and spray-json dependency
- Rename "service" to "application"
### 0.2.0
- Merge ets-poms-dependencies with ets-poms-module-parent
### 0.1.0
- Initial release
