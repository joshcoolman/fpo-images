# For Position Only - Images
### Some utility resouces for bringing temp images into personal UX projects when in development. For fun and for free.

:rocket: [Link to Unsplash](https://unsplash.com)

### Usage

```JSX
import React, { useEffect } from 'react';
import { avatars } from "@uxui-guy/fpo-images"
function App() {
  useEffect(() => {
    console.log(avatars);
  }, [])
  return (
    <Row>
      {avatars.map((el, i) => (
        <Image src={el} key={i} size={120} />
      ))}
    </Row>
  );
}
```

### Result(ish)
![screenshot](https://firebasestorage.googleapis.com/v0/b/images-aae96.appspot.com/o/GITHUB%2Ffpo-image-example.jpg?alt=media&token=48e282fe-7c51-474c-8c15-271a45738b83)

