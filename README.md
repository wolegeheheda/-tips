常见算法题记
===
## 动态规划-tips
递归画递归树   
递归算法时间复杂度 = 子问题个数×解决一个问题所需时间  
备忘录、dp 自顶向下和自下而上对其优化  
## 回溯算法-tips
算法框架
```
def backtrack(...):
    for 选择 in 选择列表:
        做选择
        backtrack(...)
        撤销选择
```
