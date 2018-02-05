# \<app-localforage\>

A Polymer 2.0 element to store data via localForage.

## Example
```html
<paper-input label="First Name" value="{{app.first_name}}"></paper-input>
<paper-input label="Last Name" value="{{app.last_name}}"></paper-input>
<br>
<paper-checkbox checked="{{app.over18}}">18 Years or Older</paper-checkbox>
<app-localforage
        key="example_name"
        data="{{app}}"
        config='{"name":"wc_example"}'
        default-value='{"over18":true}'>
</app-localforage>
```

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
