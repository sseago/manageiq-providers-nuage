# Change Log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)


## Unreleased as of Sprint 85 ending 2018-05-07

### Added
- Prefix Nuage events with "nuage" [(#84)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/84)
- Harden refresh parser [(#71)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/71)

## Unreleased as of Sprint 83 ending 2018-04-09

### Added
-Don't raise exceptions from within AMQP callbacks [(#78)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/78)

## Unreleased as of Sprint 82 ending 2018-03-26

### Added
- Also connect to CNAAlarms AMQP topic [(#73)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/73)

## Unreleased as of Sprint 81 ending 2018-03-12

### Added
- Don't run EventCatcher when user opts-in for "None" [(#69)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/69)

## Unreleased as of Sprint 79 ending 2018-02-12

### Added
- Redirect logs into log/nuage.log file [(#66)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/66)
- Add `stop_event_monitor_queue_on_change` method [(#65)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/65)

## Gaprindashvili-1 - Released 2018-01-31

### Added
- Implement graph inventory refresh for network manager [(#13)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/13)
- Provide extensive unit tests for legacy refresher [(#12)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/12)
- Install qpid_proton for Travis [(#11)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/11)
- Assign :ems_ref to the event [(#59)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/59)
- Upgrade qpid_proton related stuff to support v0.19.0 [(#58)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/58)

### Fixed
- Fix exception handing for credential validation on raw_connect [(#40)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/40)
- Fix a problem when no policy groups exist [(#4)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/4)
- Fix protocol selection when adding a new nuage provider [(#45)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/45)
- Human readable error when selecting wrong security protocol [(#43)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/43)
- Return empy list instead of nil for responses with empty bodies [(#53)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/53)

## Unreleased as of Sprint 78 ending 2018-01-29

### Fixed
- Add name method [(#62)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/62)

## Unreleased as of Sprint 72 ending 2017-10-30

### Added
- Enable Nuage network manager [(#33)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/33)
- Update raw_connect to simplify validation from UI [(#32)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/32)
- Use AMQP fallback endpoints when available [(#30)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/30)
- Connect events to targeted refresh [(#28)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/28)
- Implement targeted refresh for NetworkManager [(#20)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/20)
