# iframe-worker-demo

利用 Chrome OOPIF 策略，验证把 iframe 当 worker 用，详情可查看[把 iframe 当作 worker 使用](https://juejin.cn/post/6973128378522009613/)

## 运行

```sh
> http-server
> cd other
> http-server --cors
```

把index.html的iframe地址修改为你本机ip其中一个地址，非127.0.0.1，再打开\

## 相关链接

https://stackoverflow.com/questions/11510483/will-a-browser-give-an-iframe-a-separate-thread-for-javascript
