# What is this for?

Get perfect shadows for images everytime when you dont have idea what to do.

# Installation

`npm i shadowizard --save`

Then...

```

import { shadowizard } from 'shadowizard';

shadowizard({
    shadow_type: 'soft',
    padding: false
})


```

## Options

Shadowizard supports 2 options, both of which are options;

* *shadow_type* - _hard / soft_ (Defaults to soft)
* *padding* - _boolean_ (Defaults to false)