
## $data负责代理
e.g
```js
let data = {
    apple: 'red'
}
let vm = new Vue({
    data: data
})
console.log(vm.$data === data) // true
```