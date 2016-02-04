# Ember-route-action [![Build Status](https://travis-ci.org/peec/ember-route-action.svg)](https://travis-ci.org/peec/ember-route-action) [![Ember Observer Score](http://emberobserver.com/badges/ember-route-action.svg)](http://emberobserver.com/addons/ember-route-action)


Do you want to do this?

`{{some-link click=(transition-to "test" 'arg-to-route')}}`

Then this addon is for you. This is a very simple addon that gives you access to a helper (`transition-to`).

## Requirements

Requires Ember `2.3.0+` ( we use `Ember.getOwner` API, which was introduced in 2.3.0 ).


## Installation

* `git clone` this repository
* `npm install`
* `bower install`

## Running

* `ember server`
* Visit your app at http://localhost:4200.

## Running Tests

* `npm test` (Runs `ember try:testall` to test your addon against multiple Ember versions)
* `ember test`
* `ember test --server`

## Building

* `ember build`

For more information on using ember-cli, visit [http://www.ember-cli.com/](http://www.ember-cli.com/).
