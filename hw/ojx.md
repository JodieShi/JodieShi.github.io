[TOC]
# oj
## 考察范围
## 真题
1. 版本比较   
[leetcode 165](https://leetcode-cn.com/problems/compare-version-numbers/)
2. TLV解析   
[oj/模拟自测]()
3. 学生信息排序   
```
给出一组学生信息数据，包括每个学生的学号，身高，体重等信息，按照身高-体重-学号的优先级进行排序。
```
4. 前N个最大和对   
```
给出两个有序数组A，B和一个数字N，求前N个最大和数字对的和。
最大和数字对(a, b)满足：a属于A，b属于B，(idxOfa, idxOfb)唯一。
```
## 注意点
1. 读题   
- 明确题意
- 判断考察点：逻辑处理，边界条件处理，语言特性，算法思想（排序，搜索），数学推理
2. 输入输出处理   
- 安全函数
- 进制转换
- 类型转换
- 多维数组，动态数组（指针变量）
3. 善用C标准库   
- 字符串处理：strstr，strchr，strcmp，strcat，strtok，sscanf，sprintf，对应安全函数及返回值
- 排序与搜索：qsort，bsearch，通过字符串数组排序，单词搜索等简单例子练习comp函数的写法
- 其他库函数：isalpha，isdigit等
- hash
4. clean code要求   
- 扣分项：codingstyle，codemars规则，cmetrics圈复杂度
- 暂不扣分：建议项，编译告警
5. 调试与提交   
- 调试：wecode提前配置好运行调试环境
- 提交：部分通过时取最后一次提交结果计算成绩，务必保证最后一次提交编译通过
## 参考
1. 考试范围
2. 编程练习
3. wecode使用
4. 编码规范
