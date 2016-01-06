# Simple Redux Example

Perhaps this could even be called _Simplest_ Redux Example :) 

After I wrapped my brain around Redux, I wanted to make the most minimal working example for both my own learning and hopefully to benefit others. 

## build && test || start 

* `npm run build` -- webpack build
* `npm start` -- Do the thing.
* `npm test` -- Well, run the tests.

After `git clone`ing the project and `npm install`ing, you can run `npm run build` to have webpack glue the ESNext into a single bundle that Node can natively run. Then you can either run `npm test` or `npm start`. The former runs `tests/index.js` and the latter runs the globbed file. 

### How it works

As described above, this was the most minimal example of a working Redux app that I could dream up while still maintaining the general structure of what you would use for a 'real'/larger app. 

For an even simpler version you could do it all in one file, but I wanted to preserve the separation of concepts that I've seen in other Redux apps so as to best understand the 'moving peices'. 

#### `src/`

```
// Coming soon..
```

##### `actions.js`

##### `reducers.js`

##### `store.js`

##### `index.js`

#### `tests/index.js`
