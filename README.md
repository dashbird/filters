# Logbird rules library

[Logbird](https://logbird.io) is a service that processes log streams to find events and activate triggers for those events.

Logbird uses it's own query language to match log events and extract data from them. One of the use-cases for Logbird is to catch errors from applications by matching failed events.

This repository is a collection of community-managed filters that span services and runtimes so it would be easy for users to achieve event-alerting for their applications. When creating a new filter, Logbird offers a way to run it against test-cases (think of it like unit testing) and make sure he filter matches what you would expect. We encourage you to run these tests when contributing here.

The library JSON is displayed in a searchable manner here https://logbird.io/docs/rules/rule-library/
