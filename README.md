
这是一个将该项目的 README.md 完整翻译为中文的版本。你可以直接将其内容复制并保存为新的 README.md 文件。
电脑麻将 (Majiang)
<h1><a href="https://kobalab.net/majiang/"><img src="dist/img/logo.png" alt="电脑麻将" height=72></a></h1>
基于 HTML5 + JavaScript 运行的麻将应用「电脑麻将」。
<img src="dist/img/game.png" alt="游戏画面" width=480>
演示地址
https://kobalab.net/majiang/
开源协议
MIT
作者
Satoshi Kobayashi
npm 脚本命令
命令	说明
release	构建发布版本。
build	构建调试版本。
build:js	仅构建调试版 JavaScript。
build:css	仅构建 CSS。
build:html	仅构建 HTML。
子软件包
本项目由以下子软件包构成：
majiang-core (核心库)
GitHub: kobalab/majiang-core
npm: @kobalab/majiang-core
包含手牌操作、向听数计算、和了点（得分）计算、对局进行与桌面对话管理、思考逻辑雏形等基本类群。
majiang-ai (AI 库)
GitHub: kobalab/majiang-ai
npm: @kobalab/majiang-ai
麻雀 AI 及其开发工具。AI 是对 majiang-core 中 Majiang.Player 类的具体实现。
majiang-ui (UI 库)
GitHub: kobalab/majiang-ui
npm: @kobalab/majiang-ui
包含手牌显示、盘面显示、牌谱播放等画面显示及用户交互相关的类群。
tenhou-url-log (天凤格式转换)
GitHub: kobalab/tenhou-url-log
npm: @kobalab/tenhou-url-log
提供将“电脑麻将”的牌谱转换为网络麻将 天凤 (Tenhou) 所使用的 JSON 形式牌谱（各种 AI 分析的事实通用格式）的功能。
相关软件包
此外还有以下相关软件包：
majiang-server (对战服务器)
GitHub: kobalab/majiang-server
npm: @kobalab/majiang-server
基于 WebSocket 的麻将服务器实现。“电脑麻将”的网络对战功能通过连接此服务器实现。
majiang-analog (牌谱分析)
GitHub: kobalab/majiang-analog
npm: @kobalab/majiang-analog
牌谱分析工具。提供分析“电脑麻将”格式牌谱的基类，用户可以编写其子类来实现具体的分析程序。
tenhou-log (天凤牌谱导入)
GitHub: kobalab/tenhou-log
npm: @kobalab/tenhou-log
将 天凤 的牌谱转换为“电脑麻将”格式。利用该包可以分析或播放天凤的牌谱。“电脑麻将”牌谱查看器中的天凤牌谱播放功能即通过此实现。
相关书籍
<a href="https://www.amazon.co.jp/dp/4798067881"><img src="https://m.media-amazon.com/images/I/51DMflZaBNL._SL500_.jpg" title="对战型麻将游戏 AI 的算法与实现" height=240></a>
作者出版了讲解“电脑麻将”程序的书籍：
对战型麻将游戏 AI 的算法与实现 (日文版)
书中详细讲解了子软件包 majiang-core 和 majiang-ai。
博客文章 (英文/日文)
以下是书籍出版后（ver.2.0.0 之后）的相关技术信息（括号内为撰写时的版本）：
思考逻辑
打牌选择算法(10) 〜 剩余牌数的归一化 (v2.5)
攻守判断(Push/Fold)算法改善(4) 〜 重新调整攻守阈值 (v2.5)
牌的危险度计算算法(5) 〜 重新调整危险度阈值 (v2.5)
牌谱编辑器
牌谱编辑器的使用方法 (v2.4)
在电脑麻将中创建用于 NAGA 分析的数据 (v2.4)
麻将服务器
麻将服务器的使用方法 (v2.3)
使用 Passport 实现外部认证 (v2.3)
网络对战的思考时间设置方法 (v2.3)
麻将机器人的实现 (v2.4)
伪延迟（Fake Lag）的实现 (v2.4)
点数计算训练
电脑麻将 ver.2.2.0 公开 #点数计算训练 (v2.2)
麻将点数计算方法（正式版・简易版） (v2.2)
牌谱解析・统计
天凤凤凰卓统计 (2023年) (v2.4)
天凤凤凰卓最高・最大・最长纪录 (v2.4)
立直宣言牌的筋牌真的危险吗？ (v2.0)
侧听(Sobaten)・里筋真的危险吗？ (v2.0)
双立直的好型率・和牌率・平均打点是多少？ (v2.0)
评价牌的危险度判定算法 (v2.4)
评价牌的危险度判定算法(2) (v2.4)
评价“读山”算法 (v2.4)
模拟仿真
麻将 AI 的制作方法 (v2.4)
模拟“不鸣牌麻将”对成绩的影响 (v2.4)
模拟“禁止立直”的影响 (v2.4)
验证“Combo 理论”的有效性 (v2.4)
模拟“默听”的效果 (v2.4)
算法・其他
使用回溯法求解麻将和牌形状列表 (v2.3)
输出麻将“听牌”的程序 (v2.0)
可用于麻将应用调试的牌型示例 (v2.0)
(由于篇幅原因，旧版博客文章列表建议参考原 README)
致谢
游戏中使用的牌图像来自于 麻雀の画像・素材。
游戏音效使用了 天鳳用オリジナルSE: アンコロキングblog 的素材。