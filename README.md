# Minimalist Deno Blog
A minimalist Deno blog template forked from [Ev's Deno Blog](https://github.com/evbogue/denoblog).

Write an `index.js` file

```
import { blog } from './blog.js'

blog({
  title: "Tyron's Blog",
  avatar: 'https://avatars.githubusercontent.com/u/13947166?v=4',
  author: 'Tyron Love',
  description: "Proud Dad. <br>Lover of one Exquisite human. <br>Cartoonist for pretend.",
  background: "#f5f5f5",
  links: [
    { title: 'Twitter', url: 'https://twitter.com/tyron_love'},
    { title: 'Bogbook', url: 'https://bogbook.com/#TIZGEEjhlzfr0+15ZXO0+03vSLfDJEIFUKwXjeVGUQQ='} 
  ]
})
```

and start it with `deno run --allow-all index.js`


---
MIT
