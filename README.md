# Vein_zhCN
本项目用于游戏Vein简体中文翻译工作流。对Game.locres.csv进行更新后，会自动打包为pak文件。
## 使用方式
把pak文件放到Vein\Vein\Content\Paks中。
## 欢迎pull requests
Game.locres.csv早期进行了一次AI翻译，存在比较多错误，而且由于一些AI翻译难以理解，后来游戏更新的条目暂未进行翻译。欢迎进行改正及翻译。

csv可以进行线上编辑，或者线下使用普通文本编辑器编辑，如果使用Excel编辑，需要先另存为UTF-8-BOM才能让Excel按照UTF-8读取。
### 翻译规则
* CSV文件使用英文逗号分开3列，第一列为key不可更改，第二列为source英文原文，第三列为Translation中文翻译。
* 不要对<>和{}标签翻译
* 不要对设置中的Low Medium High Custom等进行翻译，会导致更改设置时，页面不变动。
## 工作流用到的工具
https://github.com/amrshaheen61/UE4LocalizationsTool

https://github.com/trumank/repak
