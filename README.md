runcommand/user-reset-password
==============================

Reset passwords for one or more WordPress users.

[![Build Status](https://travis-ci.org/runcommand/user-reset-password.svg?branch=master)](https://travis-ci.org/runcommand/user-reset-password)

Quick links: [Using](#using) | [Installing](#installing) | [Support](#support)

## Using

~~~
wp user reset-password <user>... [--skip-email]
~~~

**OPTIONS**

	<user>...
		Specify one or more user logins or IDs.

	[--skip-email]
		Don't send an email notification to the affected user(s).

## Installing

Installing this package requires WP-CLI v0.23.0 or greater. Update to the latest stable release with `wp cli update`.

Once you've done so, you can install this package with `wp package install runcommand/user-reset-password`.

## Support

This package is free for anyone to use. Support is available to paying [runcommand](https://runcommand.io/) customers.

Think you’ve found a bug? Before you create a new issue, you should [search existing issues](https://github.com/runcommand/sparks/issues?q=label%3Abug%20) to see if there’s an existing resolution to it, or if it’s already been fixed in a newer version. Once you’ve done a bit of searching and discovered there isn’t an open or fixed issue for your bug, please [create a new issue](https://github.com/runcommand/sparks/issues/new) with description of what you were doing, what you saw, and what you expected to see.

Want to contribute a new feature? Please first [open a new issue](https://github.com/runcommand/sparks/issues/new) to discuss whether the feature is a good fit for the project. Once you've decided to work on a pull request, please include [functional tests](https://wp-cli.org/docs/pull-requests/#functional-tests) and follow the [WordPress Coding Standards](http://make.wordpress.org/core/handbook/coding-standards/).

Github issues are meant for tracking bugs and enhancements. For general support, email [support@runcommand.io](mailto:support@runcommand.io).


