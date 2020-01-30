## 你知道vue3有哪些新特性吗？
1. 编译器
    - 使用模块化架构
    - 优化 “Block tree”
    - 更激进的 static tree hoisting 功能
    - 支持 Source map
    - 内置标识符前缀（又名 “stripWith”）
    - 内置整齐打印（pretty-printing）功能
    - 移除 source map 和标识符前缀功能后，使用 Brotli 压缩的浏览器版本精简了大约 10KB
2. 运行时
    - 速度显著提升
    - 同时支持 Composition API 和 Options API，以及 typings
    - 基于 Proxy 实现的数据变更检测
    - 支持 Fragments
    - 支持 Portals
    - 支持 Suspense w/ async setup()