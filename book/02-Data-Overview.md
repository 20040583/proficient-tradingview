
# 数据处理概述

在 图表库 的配置代码中，只需要按照规定的格式通过 JSAPI 配置给定数据即可显示图表。

### 1、数据来源

图表库 是基于 JavaScript 编写的图表库，使用UDF时，自身具有直接获取数据服务器数据的能力，使用WS直接调用jsapi时，需要编写获取数据的前端代码。

### 2、数据处理和交互

支持数据的处理，一般是用 JavaScript 针对返回的 JSON 数据、字符串数据进行数组、对象的操作，最终转换成 图表库 需要的格式。

### 3、JSAPI与UDF的区别