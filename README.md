# Logbird rules library

[Logbird](https://logbird.io) is a service that processes log streams to find events and activate triggers for those events.

Logbird uses it's own query language to match log events and extract data from them. One of the use-cases for Logbird is to catch errors from applications by matching failed events.

This repository is a collection of community-managed filters that span services and runtimes so it would be easy for users to achieve event-alerting for their applications.

The library is also available in a friendly format in [our documentation](https://logbird.io/docs/rules/rule-library/).

## You are welcome to contribute

If you have suggestions for common filters that you would like to share with the Logbird community, please submit a pull request.

When creating a new filter, Logbird offers a way to run it against test-cases (think of it like unit testing) and make sure the filter matches what you would expect. We encourage you to run these tests when contributing here. To run a test, signin to [Logbird](https://app.logbird.io/), go to **Filters** in the left menu then click **Add rule**. You will see a modal screen similar to the one below. Enter your pattern and a few example logs below (or pull from AWS CloudWatch) and click **Run tests**.

![UI Screenshot Test Pattern](https://github.com/dashbird/filters/blob/master/static/img/screenshot-logbird-rule.png?raw=true)
