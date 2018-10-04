# Changelog

User-visible changes worth mentioning.

## master

- [#] Description here

## 4.2.0

- [#32] Add `confidential` field for Doorkeeper >= 4.4
- [#34] Fixes to support Doorkeeper +. 4.4

## 4.1.0

- Update to upstream doorkeeper
- Fix mixins Access Token value generation to properly process custom
  token generator class methods
- Lazy load ORM models using ActiveSupport hooks
- Clear code base from the dead code
- Refactor mixins

## 4.0.1

- Code refactoring
- [#26] Lazy ORM models loading
- [#28] Mongoid 6 and 7beta support
- Test against Rails 5.2
- Update to upstream of Doorkeeper
