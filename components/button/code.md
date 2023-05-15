
# Code

---

## Live Code snippet

Display any other type of code snippet with a *Code* block:

```javascript  
import React, { useState } from 'react';
import Calendar from 'react-calendar';
import 'react-calendar/dist/Calendar.css'

export default function Component() {
  const [value, onChange] = useState(new Date());

  return (
    <div>
      <Calendar onChange={onChange} value={value} />
    </div>
  );
}  
```

## Storybook story

Or embed a Storybook story with the *Storybook* block:

Display content from a Storybook URL. This URL can be public, private, or behind a VPN. You must be logged in with Storybook before it will show up in the documentation.

1. Select *Storybook* from the block menu

1. Enter the URL of a Storybook story and click *Embed*

1. The story will be displayed — click on the block to open the story in a new window

1. You can optionally resize the container vertically by using the resize handle (accessible on hover)

  
[Open Storybook Canvas](https://6195b518b76f57003aa69b4c-ynczzfqqyq.chromatic.com/iframe.html?addons=0&stories=0&panel=false&nav=false&id=navigation-navigation-stylednavigation--default&full=1&viewMode=story)  


You can also show more details about the story and interact with its properties by enabling the [Storybook Info Add-on](https://storybook.js.org/addons/@storybook/addon-info).

1. Hover over the block to access the display menu

1. Turn the toggle *ON* to enable Add-ons

  
[Open Storybook Canvas](https://6195b518b76f57003aa69b4c-ynczzfqqyq.chromatic.com?addons=1&stories=0&panel=true&nav=false&path=%2Fstory%2Futilities-interactivelist--select-on-focus)  


```javascript  
  
```

```javascript  
import React from 'react';
export default function Button(props) {
 return (
   <button>
     Click me!
   </button>
 );
}  
```

```javascript  
  
```