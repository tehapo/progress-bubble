progress-bubble
===============

![Screenshot](https://raw.githubusercontent.com/tehapo/progress-bubble/master/screenshot.png)

Simple Polymer-based web component to display a circular progress bar and optionally some content in the middle.

See a [live demo](http://tehapo.com/experiments/progress-bubble/).

## Getting Started

### Installation
```bash
bower install progress-bubble --save
```

### Usage
```html

<progress-bubble value="8" stroke-width="10" maxgauge="10">
              <strong>80%</strong>
</progress-bubble>

<!-- Custom styling and stroke-width -->
<style is="custom-style">
    progress-bubble {
        --progress-bubble-stroke-color: rgba(255, 0, 0, 0.8);
        --progress-bubble-stroke-linecap: butt;
        --progress-bubble-bg-stroke-color: rgba(193, 193, 193, 0.2);
        --progress-bubble-background: transparent;
        --progress-bubble-reflection-display: none;
    }
</style>
<!-- Set an interval with a min and max value, And a starting angle and an ending angle equals to 180 degree, 
set isinside value to block the value of the progress bar inside the interval-->
<progress-bubble value="42" stroke-width="10" alpha="180" max="110" min="-10" beta="180" isinside="true">
              <strong>42</strong>
</progress-bubble>
```

### Development
Use ```polyserve``` during development as instructed in [Create a reusable element](https://www.polymer-project.org/1.0/docs/start/reusableelements.html) article.
