
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

  
[Open Storybook Canvas](https://6195b518b76f57003aa69b4c-ynczzfqqyq.chromatic.com/iframe.html?addons=0&stories=0&panel=false&nav=false&id=navigation-navigation-stylednavigation--default&full=1&viewMode=story)  


  
[Open Storybook Canvas](https://6195b518b76f57003aa69b4c-ynczzfqqyq.chromatic.com?addons=1&stories=0&panel=true&nav=false&path=%2Fstory%2Futilities-interactivelist--select-on-focus)  
