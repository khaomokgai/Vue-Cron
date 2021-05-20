# 修改使用 vue-crontab 开发时遇到的 bug

- 秒、分钟、小时、日、月、周、年下拉选项回填问题
- 小时下拉 0-59 问题
- 周、年范围回填问题
- 选择错误提示不清晰问题
- 支持获取反编译结果 list

# [demo](https://khaomokgai.github.io/vCrontab/dist/index.html)

## 使用方式

```javascript
<Crontab
:expression="cronExpression"
@getValue="getValue"
:resultList="resultList"></Crontab>

// expression: 回填数据时使用
// getValue: 获取cron表达式
// resultList: 获取反编译后的结果


```

# vue-crontab 源码地址

https://github.com/small-stone/vCrontab
