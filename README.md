### Countable
---
https://github.com/RadLikeWhoa/Countable

```
npm i --save-dev countable
yarn add --dev countable
```

```js
Countable.count(document.getElementById('text'), counter => console.log(this, counter))

Countable.on(area, counter => console.log(counter))

Countable.off(area)

Countable.once(area, counter => console.log(counter))

Countable.enabled(area)


```

```
{
  hardRetruns: false,
  stripTags: false,
  ignore: []
}
```

