# -
文件-选项-加载项-分析工具库-转到-选定分析工具库-确定
数据-数据分析-选择描述统计-输入区域选择-新工作表组，汇总统计
计算男女人数：单元格上下输入男女=countif（数据所在单元格，输出单元格）按ctrl+shift+enter
利用Frequency函数计算各分数段人数-在单元格内输入每段分数的范围或者分数段，选中所要输出的单元格=Frequency（数据所在单元格，输出单元格）-按ctrl+shift+enter
利用if函数对分数进行分组，=IF(D2>89,"90以上",IF(D2>79,"80-90",IF(D2>69,"70-80",IF(D2>59,"60-70","60以下"))))    D2为数据单元格
