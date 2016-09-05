<p align="center">
  <img src="https://cdn.rawgit.com/meteor/blaze/master/images/logo.svg" width="260" />
</p>

[![Slack Status](http://slack.blazejs.org/badge.svg)](http://slack.blazejs.org)
[![CircleCI Status](https://circleci.com/gh/meteor/blaze.svg?style=shield)](https://circleci.com/gh/meteor/blaze)

## What is Blaze?

Blaze is a powerful library for creating user interfaces by writing reactive HTML templates.  Compared to using a combination of traditional templates and jQuery, Blaze eliminates the need for all the "update logic" in your app that listens for data changes and manipulates the DOM.  Instead, familiar template directives like ``{{#if}}`` and ``{{#each}}`` integrate with [Tracker's](https://meteor.com/tracker) "transparent reactivity" and [Minimongo's](https://meteor.com/mini-databases) database cursors so that the DOM updates automatically.

Blaze is sometimes compared to frameworks like React, Angular, Ember, Polymer, Knockout, and others by virtue of its advanced templating system.  What sets Blaze apart is a relentless focus on the developer experience, using templating, transparent reactivity, and interoperability with existing libraries to create a gentle learning curve while enabling you to build world-class apps.

### Blaze has two major parts:

* A template compiler that compiles template files into JavaScript code that runs against the Blaze runtime library.  Moreover, Blaze provides a compiler toolchain (think LLVM) that can be used to support arbitrary template syntaxes.  The flagship template syntax is Spacebars, a variant of Handlebars, but a community alternative based on Jade is already in use by many apps.

* A reactive DOM engine that builds and manages the DOM at runtime, invoked via templates or directly from the app, which features reactively updating regions, lists, and attributes; event delegation; and many callbacks and hooks to aid the app developer.

## Quick Start

Blaze is a [Meteor](http://meteor.com/)-only package for now. Sooner we will have Blaze on npm so you can use it in your stack.

A new Meteor project has Blaze included.

## Get involved

We'd love for you to help us build Blaze. If you'd like to be a contributor,
check out our [contributing guide](/Contributing.md).

Also, to stay up-to-date on all Blaze related news and the community you should
definitely [join us on Slack](http://slack.blazejs.org)

See the current [roadmap](https://github.com/meteor/blaze/milestones) and consider helping with any of the tasks on the roadmap.

If you want to contribute with any suggestions or report a problem, open an issue: [issues](https://github.com/meteor/blaze/issues)

## License

Blaze is available under the MIT license
