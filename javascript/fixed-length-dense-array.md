# Fixed-Length Dense Array

``` javascript

let arr;

arr = Array(3).fill(undefined); // performance: fastest 🚀

arr = [...Array(3)];            // performance: fast 🚗

arr = Array.from({ length: 3}); // performance: slowest 🚶‍♂️

``` 