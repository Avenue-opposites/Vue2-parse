# Vue源码解析
* mustache模板引擎
    - 底层原理
        - 使用模板字符串编译为tokens结合数据解析为DOM字符串
        - tokens是一个二维数组,他是抽象语法树和虚拟节点的开山鼻祖