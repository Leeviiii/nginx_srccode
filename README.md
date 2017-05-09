# nginx_srccode
nginx源码分析

- [Nginx内部用到的数据结构](./ngx_datastructure/ngx_datastructure_readme.md)
  - 内存池
  - [hash表](./ngx_datastructure/ngx_hash.md)
  - [支持通配符的hash表](./ngx_datastructure/ngx_hash.md)
  - [ngx_queue_t双端环形链表](./ngx_datastructure/ngx_queue_t.md)

- Nginx架构
  - 底层网络事件
  - 配置解析
  - 模块加载
  - 如何写一个hello world的nginx模块
  - 反向代理的原理
- Nginx作为http server
  - http模块的配置解析以及结构
  - http模块的处理过程
  - http模块server是如何查找匹配的的
  - http模块location是如何查找匹配的的

- Nginx rtmp模块
  - rtmp协议握手过程分析
