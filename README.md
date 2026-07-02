# Steam-Inventory-Card-Value-Calculator
一键计算 Steam 库存中所有集换式卡牌的市场总价值的油猴脚本。支持多货币切换、暂停/继续、自定义并发数与请求间隔，并显示完整的价格查询日志
# 用法
1. 首先在你的浏览器安装 [油猴/篡改猴(Tampermonkey)插件](https://www.tampermonkey.net/index.php?locale=zh)。
2. [点击这里安装](https://greasyfork.org/zh-CN/scripts/585273-steam-%E5%BA%93%E5%AD%98%E5%8D%A1%E7%89%8C%E6%80%BB%E4%BB%B7%E8%AE%A1%E7%AE%97%E5%99%A8)油猴脚本
3. 打开网页版steam，点击库存油猴脚本即可生效，在这里可以设置你的参数配置，例如货币单位/并发线程数/查询间隔/ 建议使用默认参数,过快可能会触发Steam的保护机制
<img width="345" height="334" alt="image" src="https://github.com/user-attachments/assets/e1bbb4de-06d8-49e5-8c4a-7ee75ab5a12d" />

4. 点击计算库存总价，即可自动开始计算库存内所有卡牌价值的总数，价格获取的是当前卡牌挂售的最低价

>  **提示：** 如果你发现计算完毕后很多物品没有价格，那么就是触发了 Steam 的保护机制。你需要更换一个网络/加速器节点/VPN 节点，随后清除浏览器的 Cookie。
