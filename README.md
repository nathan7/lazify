

# lazify

  convenient wrapper for lazy promises

## Installation

    $ npm install lazify

  or

    $ component install nathan7/lazify

## Example

```js
var req = lazify(function() {
  return xhr('http://blah.com')
})
```

## API

### lazify :: (-> Promise a) -> LazyPromise a

  Takes a function that returns a promise and returns a lazy promise.
  The edge case of returning a value or throwing an error is handled.

## License

  MIT
