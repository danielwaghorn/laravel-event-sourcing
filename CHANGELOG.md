# Changelog

All notable changes to `laravel-event-sourcing` will be documented in this file:

## 1.0.3 - 2019-11-01

- Provide docblocks to AggregateRoot class (#31)

## 1.0.2 - 2019-10-27

- Implemented missing HandleDomainEventJob interface
- Use a UUID field when possible for storing UUIDs

## 1.0.1 - 2019-10-11

- Fix an issue with encoding the `event_properties` when they're already a string

## 1.0.0 - 2019-09-20

- initial release

This package supercedes [spatie/laravel-event-projector](https://github.com/spatie/laravel-event-projector) 

To learn how to upgrade from laravel-event-projector v3 to laravel-event-sourcing v1 , read [our upgrade guide](https://github.com/spatie/laravel-event-sourcing/blob/master/UPGRADING.md)
