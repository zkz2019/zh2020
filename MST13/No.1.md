## watch 和 computed 有什么区别？
    1. watch
        - 用于监听数据变化，比如监控页面一个变量值的改变需要进行的操作
    2. computed
        - 时用于处理复杂的逻辑运算的，它不必每次都像methods一样调用
        - 它有一个缓存机制，只有在依赖发生改变的时候才会执行
        - 可以把方法封装到里面，只返回一个数据
        - 可以进行数据的设置