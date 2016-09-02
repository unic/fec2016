# Let's make some noise

## Result

https://vimeo.com/181163325

## Prerequisites

* Lots of cables and knobs
* [Open Sound Module](http://www.rebeltech.org/products/open-sound-module/) or something similar

## Setup

### Variant A: Meteor

1. Install [meteor](https://www.meteor.com/)
2. Run `meteor`

### Variant B: socket.io, Express and React

1. Check out `feature/socketio` branch
2. Run `npm i`
3. Run `npm run dev`

## Use

1. Open `http://localhost:3000`
2. Start communicating with an OSM (see above) on port `9000`
5. Access port `3000` of your machine from another device in the same network to collaborate
