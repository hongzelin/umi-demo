# umi-demo
umi demo 实现用户管理的CRUD。

# 扩展
- 项目直接通过umi的脚手架进行搭建 yarn create umi，并不是通过dva-cli.

# 优化总结
- 增加、删除、改修功能后，应该获取当前的页数，再做对应的查询。
- 对于modal状态show、hide的控制，直接在modal中做状态的控制，不需要传递 visible；内容可以通过props children属性。

# 参考
https://github.com/sorrycc/blog/issues/62
