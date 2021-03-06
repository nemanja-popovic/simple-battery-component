# simple-battery-status

Element used to show battery status using Battery API.

![alt tag](https://raw.githubusercontent.com/nemanja-popovic/simple-battery-component/master/battery100%25.PNG)

## How to install

Install simply by executing: 

    bower i simple-battery-component -S

command. Bower is required and explanation how to install bower can be found in `Dependencies` part of this Readme.md file.

## How to use

In order to use this element first add refrence to the simple-battery-status.html. Then just use the element

```html
<simple-battery-status detect></simple-battery-status>
```

anywhere in your page. Also take a look in demo/index.html file for more examples.

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install

## Playing With simple-battery-status

If you wish to work on this element in isolation, we recommend that you use
[Polyserve](https://github.com/PolymerLabs/polyserve) to keep your element's
bower dependencies in line. You can install it via:

    npm install -g polyserve

And you can run it via:

    polyserve

Once running, you can preview element at
`http://localhost:8080/components/simple-battery-status/`.
