# generatePath
easily create urls from string

## Example
```js
import generatePath from './generatePath'
const urls = {
home: '/',
blog : '/blog/:title/:year/:month'
}
generatePath(urls.blog,{
  title: 'some-cool-title',
  year: new Date().getFullYear(),
  month: new Date().getMonth() + 1
})

// output: /blog/some-cool-title/2021/10

```

