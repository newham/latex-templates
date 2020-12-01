# Latex 模板

## 期刊

出版社|期刊|更新时间
-------|----|------------
[IEEE](https://ieeexplore.ieee.org/)|[Access](/IEEE/access)<br>[Internet of Things Journal](/IEEE/IEEETransactions_LaTeX)<br>[Conference](/IEEE/Conference-LaTeX-template_10-17-19)|2020-11-30
[Springer](https://www.springer.com/)|[Journal](/Springer/LaTeX_DL_468198_240419)|2020-11-30
[ELSEVIER](https://www.sciencedirect.com/)|[Journal](/ELSEVIER/els-cas-templates)|2020-11-30
[MDPI](https://www.mdpi.com/)|[Sensors](/MDPI/MDPI_template)|2020-12-1

## 自定义样式(my.sty)

命令|说明|用法
---|----|----
\fig|图|`\fig{文件路径}{标题}{标签}`
\reffig|引用表格|`\reffig{标签}`
\equa|单行公式|`\equa{公式}`
\algor|算法|`\algor{标题}{标签}{算法体}{输入}{输出}`
\tbl|表格|`\tbl{标题}{标签}{对齐方式(c|c|c)}{表头}{表体}`
\tabincell|表格行内换行|`\tabincell{行1\\行2...\\行n}`
\changed|修改标记(用于审稿)|`\changed{改动}{问题编号(1-1)}`
