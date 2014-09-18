progress-bubble
===============

![Screenshot](https://raw.githubusercontent.com/tehapo/progress-bubble/master/screenshot.png)

Simple Polymer-based web component to display a circular progress bar and optionally some content in the middle.

At this point this is simply an experiment and is tested only on Google Chrome browser.

See a [live demo](http://tehapo.com/experiments/progress-bubble/).

## Getting Started

### Installation
```bash
bower install progress-bubble --save
```

### Usage
```html
<progress-bubble value="8" max="10">
    <strong>80%</strong>
</progress-bubble>

<!-- Custom stroke color and width -->
<progress-bubble value="8" max="10" stroke="rgba(255, 0, 0, 0.8)" stokeWidth="10">
    <strong>80%</strong>
</progress-bubble>
```
