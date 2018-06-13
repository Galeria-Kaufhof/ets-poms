# ETS Poms

[![Build Status](https://travis-ci.org/Galeria-Kaufhof/ets-poms.svg?branch=master)](https://travis-ci.org/Galeria-Kaufhof/ets-poms)

This project contains all POMs defining a ETS release.

## Technical decisions

### No SCM / Distribution Management settings
An important decision is that we configure any distribution management or scm settings in this parent POMs. We want to ensure that when you build a private lib or service, using one of the POMs as parent, you'll never accidentially release this private stuff to maven central because you inherit settings from that from the parents. 

## Changelog

### 0.1.0
- Initial release
