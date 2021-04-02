# For Position Only - Images
### Some utility resouces for bringing temp images into personal UX projects when in development. For fun and for free.

:rocket: [Link to Unsplash](https://unsplash.com)

### Usage

```JSX
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

