# dorgaren/laravel-json-api

**This package is a fork of _cloudcreativity/laravel-json-api_.
It is created to maintain _backwards compatibility_ with 0.x versions.**

Reasons:
* there is no upgrade guide nor changelog from 0.x to 1.x;
* the architecture has been changed radically, even to the point where classes become _final_;
* there is no clear (nor unclear) reasoning behind architectural decisions;
* 0.13 being the last 0.x version released; and
* 0.13 being incompatible with Laravel 5.8+.

Since currently I have to maintain at least one project that has been created when the last version was 0.12.0, extending classes that have become _final_, and also the package's architecture posing serious questions towards possible use cases having been had considered, I figured it is easier to revamp the original branch than upgrading any projects just yet.

If you face similar problems, _feel free to use this fork_. I can, while being around, guarantee that I will bump versions and even make minor modifications necessary to keep this compatible with new Laravel versions, and also that _I will respond_ when I deem anything further infeasible or unlikely.

**For any new, fresh "greenfield" projects, though, it is advisable that you use the mainline package, either 1.x or 2.0 when it will become final.**

---

Add [jsonapi.org](http://jsonapi.org) compliant APIs to your Laravel 5 application.
Based on the framework agnostic packages [neomerx/json-api](https://github.com/neomerx/json-api)
and [cloudcreativity/json-api](https://github.com/cloudcreativity/json-api).

## What is JSON API?

From [jsonapi.org](http://jsonapi.org)

> If you've ever argued with your team about the way your JSON responses should be formatted, JSON API is your
anti-bikeshedding weapon.
>
> By following shared conventions, you can increase productivity, take advantage of generalized tooling, and focus
on what matters: your application. Clients built around JSON API are able to take advantage of its features around
efficiently caching responses, sometimes eliminating network requests entirely.

For full information on the spec, plus examples, see http://jsonapi.org

## Demo

A demo application is available at [here](https://github.com/cloudcreativity/demo-laravel-json-api).

## Laravel Versions

| Laravel | This Package |
| --- | --- |
| 5.4.* | ^0.13 |
| 5.5.* | ^0.13 |
| 5.6.* | ^0.13 |
| 5.7.* | ^0.13 |

Make sure you consult the [Upgrade Guide](http://laravel-json-api.readthedocs.io/en/latest/upgrade/) when upgrading.

## Lumen

Currently we have not integrated the package with Lumen. If you use Lumen and can help, please let us know on
[this issue](https://github.com/cloudcreativity/laravel-json-api/issues/61).

## Documentation

Documentation is available on [Read the Docs](http://laravel-json-api.readthedocs.io/en/latest/).

## Status

This repository is under development. We have production applications that are using the package and extensive test
coverage of these applications.

> We are aiming for v1.0 as soon as possible. See
[this issue](https://github.com/cloudcreativity/laravel-json-api/issues/60) for progress.

## License

Apache License (Version 2.0). Please see [License File](LICENSE) for more information.

## Installation

Installation is via `composer`. See the documentation for complete instructions.

## Contributing

Contributions are absolutely welcome. Ideally submit a pull request, even more ideally with unit tests.
Please note the following:

* **Bug Fixes** - submit a pull request against the `master` branch.
* **Enhancements / New Features** - submit a pull request against the `develop` branch.

We recommend submitting an issue before taking the time to put together a pull request.
