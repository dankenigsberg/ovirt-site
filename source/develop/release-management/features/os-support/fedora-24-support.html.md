---
title: Fedora 24 Support
category: feature
authors: sandrobonazzola
feature_name: Fedora 24 Support
feature_modules: all
feature_status: Development
---

# Fedora 24 Support

## Summary

Add support for Fedora 24

## Owner

*   Name: Sandro Bonazzola
*   Email: <sbonazzo@redhat.com>

## Detailed Description

*   Support building on Fedora 24
*   Create Jenkins jobs for automated build and testing on Fedora 24
*   Create Fedora 24 Jenkins slaves
*   Verify that all the components have no regressions only due to Fedora 24

## Benefit to oVirt

*   oVirt will be able to run on Fedora 24

## Dependencies / Related Features

*   All subprojects must support Fedora 24

## Documentation / External references

*   <https://fedoraproject.org/wiki/Releases/24/Schedule>
*   <https://fedoraproject.org/wiki/Releases/24/ChangeSet>

## Testing

The whole [Test Case](http://www.ovirt.org/develop/infra/testing/test-cases/) collection must work on Fedora 24.

## Contingency Plan

The feature is self contained: if support for Fedora 24 won't be ready for 4.1.0 we won't deliver Fedora 24 RPMs.

## Release Notes

      == Fedora 24 Support ==
      Support for running oVirt on Fedora 24 (or similar) has been added.
