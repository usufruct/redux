# Examples

Redux is distributed with a few examples in its [source code](https://github.com/rackt/redux/tree/master/examples).

>##### Note on Copying
>If you copy Redux examples outside their folders, you can delete some lines at the end of their `webpack.config.js` files. They follow a “You can safely delete these lines in your project.” comment.

## Counter

Run the [Counter](https://github.com/rackt/redux/tree/master/examples/counter) example:

```
git clone https://github.com/rackt/redux.git

cd redux/examples/counter
npm install
npm start

open http://localhost:3000/
```

It covers:

* Basic Redux flow;
* Testing.

## TodoMVC

Run the [TodoMVC](https://github.com/rackt/redux/tree/master/examples/todomvc) example:

```
git clone https://github.com/rackt/redux.git

cd redux/examples/todomvc
npm install
npm start

open http://localhost:3000/
```

It covers:

* Redux flow with two reducers;
* Updating nested data;
* Testing.

## Async

Run the [Async](https://github.com/rackt/redux/tree/master/examples/async) example:

```
git clone https://github.com/rackt/redux.git

cd redux/examples/async
npm install
npm start

open http://localhost:3000/
```

It covers:

* Basic async Redux flow with [redux-thunk](https://github.com/gaearon/redux-thunk);
* Caching responses and showing a spinner while data is fetching;
* Invalidating the cached data.

## Universal

Run the [Universal](https://github.com/rackt/redux/tree/master/examples/universal) example:

```
git clone https://github.com/rackt/redux.git

cd redux/examples/universal
npm install
npm start & npm run client

open http://localhost:3000/
```

It covers:

* [Universal rendering](/docs/recipes/ServerRendering.md) with Redux and React
* Prefetching state based on input and via asynchronous fetches.
* Passing state from the server to the client

## Real World

Run the [Real World](https://github.com/rackt/redux/tree/master/examples/real-world) example:

```
git clone https://github.com/rackt/redux.git

cd redux/examples/real-world
npm install
npm start

open http://localhost:3000/
```

It covers:

* Real-world async Redux flow;
* Keeping entities in a normalized entity cache;
* A custom middleware for API calls;
* Caching responses and showing a spinner while data is fetching;
* Pagination;
* Routing.

## More Examples

You can find more examples in [Awesome Redux](https://github.com/xgrommx/awesome-redux).
