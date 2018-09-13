# cobalt

It's 2018, browsers are great, CSS Grid is here, and it's time to rethink the basics.

Cobalt is an all-purpose SCSS boilerplate with as few styles as possible. Inspired by default browser stylesheets, it's meant to make almost any HTML look readable, using "semantic" styles. It sets up a strong typographic foundation and a versatile spacing system based on margin collapsing, in addition to handling tables, code blocks, and form elements in a modern way.

It's highly customizable — almost everything is connected to sass variables — so it can quickly adapt to any kind of project. It can grow and transition from HTML prototyping all the way to production stylesheets for complex sites. Some of the options are meant to accommodate this duality of purpose, attempting to achieve a readable quasi-layout when there is none, and getting out of your way when you start building a real one.

Some `normalize.css`-style cross-browser normalization is applied, but kept to a minimum. It's okay for browsers to do their own thing sometimes.

A few extra scss partials are included with more opinionated stuff. They provide simple solutions to common web design patterns, showing how cobalt's variables and mixins can be used.

Cobalt is not a layout framework. With wide support for Grid and Flexbox, CSS layout no longer needs to rely on frameworks to achieve interesting or complex results. Old browsers? They'll be fine getting a single-column flow layout using Cobalt's readable foundation. If your HTML is good, you shouldn't need much CSS.
