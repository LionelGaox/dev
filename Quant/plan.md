# 工作计划

## 待实现

1. 通用接口定义
2. 基金

弱需求
1. VMACD
2. 波动率 + z-score
3. RSI指标

### 通用接口定义

    # 连续趋势类型
    struct response_st {
        string 	date;  // 日期
        bool 	trade; // true-买入
        int  	level; // 每次出现买入/出标志 +1
    } RES;

