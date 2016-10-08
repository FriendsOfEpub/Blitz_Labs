# Blitz_Labs
This is where the fun blitz stuff happens (R&amp;D, experiments, etc.)

Let’s test and debug new and experimental features. 

An ePub 3.0.1 file is provided in order to test in Reading Systems. 

The file is systematically tested on Reading Systems listed in the repo’s Readme.

**See `assets` folder for preview.**

Those features might be implemented in Blitz v.1 or v.2. It depends on many factors (LESS’ bloat, unexpected bugs outside official RS support list, etc.) so there is no guarantee we will implement all of them.

## Features being currently tested

- `@supports` for progressive enhancement;
- `initial-letter` for drop-caps;
- custom `list-style-type` with fallback;
- flexbox to align elements vertically on title-page (alternative to `display: table` which proves problematic in legacy RMSDK);
- CSS shapes;
- CSS masking.

## Features which may be tested

- Open type features;
- `monochrome` media query;
- `pointer` and `hover` media queries;
- a media query strategy relying on `height` instead of `width` and/or `aspect-ratio`;
- the JavaScript framework;
- an SVG framework for charts (maybe… not sure at all).

## Stuff likely to happen

- crashing Reading Systems; 
- discovering security holes;
- drinking. A lot.