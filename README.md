# What is this?

[![Release](https://github.com/amentumservices/Collector-DrawIO/actions/workflows/collect.yml/badge.svg?branch=main)](https://github.com/amentumservices/Collector-DrawIO/actions/workflows/collect.yml)

This is a project that automatically collects and creates artifacts to ease in air-gapped transfer of the latest DrawIO Release.

It runs actions as needed/manually, on GIT Commit Push or Manually

In this case, it:

- collects DrawIO Releases (Submitted and Latest)
- creates an set of ISO Files for release on Sharepoint

## Images include:

### Disk - _drawio-\<DATE>.iso_

- Latest DrawIO release
- Submitted DrawIO release v24.6.1