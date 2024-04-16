# Fruit-shopping-cart
用vue语法实现的购物车删改查、全选反选、统计总数量和总价、存储本地浏览器等
## 业务技术点总结：
1. 渲染功能： **v-if/v-else v-for :class**
2. 删除功能: **点击传参** **filter**过滤覆盖原数组
3. 修改个数：**点击传参** **find**找对象
4. 全选反选：计算属性**computed** 完整写法 **get/set**
5. 统计**选中的**总价和总数量: 计算属性**computed** **reduce**条件求和
6. 持久化到本地： **watch**监视，**localStorage**，**JSON.stringify**, **JSON.parse**
7. 示意图
[![fruit](https://img.17carat.cn/2024/04/github/fruit.png "fruit")](https://img.17carat.cn/2024/04/github/fruit.png "fruit")
