1. 暴力递归原则：可变参数类型不要比int更复杂；（上一个原则违反了，请不要违反现在的原则）必须是单一可变参数
2. 展开递归树的前几层，观察是否有重复解
3. 使用哈希表或者集合来写傻缓存，即构建记忆化搜索
4. 如果求解递归时有枚举情况，根据递归构建严格位置依赖的表结构
5. 在表结构的填值过程中使用空间压缩、状态压缩、四边形不等式、斜率优化等技巧