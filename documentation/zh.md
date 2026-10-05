<!-- ELUCENIA technical documentation · escore-de-westley · zh · no clinical/professional/rights approval -->

# Westley 评分（哮吼）

[条件、来源与许可](https://elucenia.org/zh/tools/escore-de-westley)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 意识水平

`cons`

- `0` — 正常（包括睡眠时）
- `5` — 定向障碍

### 发绀

`cian`

- `0` — 无
- `4` — 伴躁动
- `5` — 静息时

### 喘鸣

`estr`

- `0` — 无
- `1` — 伴躁动
- `2` — 静息时

### 空气进入

`ar`

- `0` — 正常
- `1` — 减低
- `2` — 显著减低

### 胸壁凹陷

`ret`

- `0` — 无
- `1` — 轻度
- `2` — 中度
- `3` — 重度

## 方法版本

Westley 1978：5项因素，0–17；哮吼

## 已记录的公式

5项相加：意识（0或5）、发绀（0、4或5）、喉鸣（0至2）、进气量（0至2）、胸壁凹陷（0至3）。总计0至17。

## 限制与适用人群

Westley 1978论文在一项干预试验中评估了20名4个月至5岁儿童，他们因急性哮吼住院且静息时持续存在喉鸣。该年龄范围描述的是原始队列，本身不能确定评分普遍适用的年龄界限。所采用的评分表和严重程度分类需要专门核对。

## 参考文献

- [Westley CR, Cotton EK, Brooks JG. Nebulized racemic epinephrine by IPPB for the treatment of croup: a double-blind study. Am J Dis Child, 1978.](https://doi.org/10.1001/archpedi.1978.02120300044008)

- [Bjornson CL, Johnson DW. Croup in children. CMAJ, 2013.](https://doi.org/10.1503/cmaj.121645)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026
