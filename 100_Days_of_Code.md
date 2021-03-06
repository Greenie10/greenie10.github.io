---
layout: default
title: 100 Days of Code
nav_order: 4
# has_children: true
---

# 100 Days of Code

## 1) Using React Router 5’s useParams

In my Routing file, I enable the passing of a parameter `id` into my Foo component:

```javascript
<Route path="/foo/:id">
  <Foo>
    <Bar />
  </Foo>
</Route>
```

This `id` is then picked up from the URL in my Foo component with `useParams()` and passed though as a prop in my Bar component.

```javascript
import { useParams } from "react-router-dom";

const Foo = () => {
  let { id } = useParams();
  return <Bar id={id} />;
};
```

The `id` would then come through into my Bar component as a destructured prop, ready to be used by a GraphQL mutation.

(see more details on [React Router 5's hooks](https://reacttraining.com/react-router/web/api/Hooks))
