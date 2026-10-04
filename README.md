# Stock Research Reports

美股每日公开研究报告，包含市场摘要和全部分析标的的详细报告。

- [最新报告索引](latest/INDEX.md)
- [每日摘要](latest/SUMMARY.md)
- [日期与文件校验清单](latest/manifest.json)
- 个股报告使用固定路径：`latest/stocks/AAPL.md`、`latest/stocks/NVDA.md` 等。

个股详情包含支撑与阻力区间、Fib、成交与事件区、技术和估值证据，以及报告中选定的纸面 setup、入场、失效与目标参考。仅完整成功的日报批次更新 `latest/`。报告日期和批次更新时间可在 manifest 中查看；旧版本保留在 Git 提交历史。

价格坐标采用各报告注明的口径，目前主要为 Futu/Moomoo 的 current-vintage QFQ。使用时应核对报告日期、行情截止时间及价格口径，避免把旧报告或不同复权口径当成当前同口径行情。星级表示独立结构证据强度；标记为仅观察或 display-only 的研究字段保持其原有权限。

公开版仅用于辅助股票分析。已移除真实持仓章节、持仓身份提示、个人账户字段，以及所有推荐仓位、买卖数量/金额、加减仓比例和分批兑现比例。大盘状态、结构区间和风险证据保留；报告不提供买多少或卖多少的建议。

## 在 ChatGPT 中使用

将下面的请求发给可访问网页的 ChatGPT，并把 AAPL 换成要分析的股票代码：

> 请先读取 https://raw.githubusercontent.com/jweng3/stock-research-reports/main/latest/manifest.json ，确认报告日期；再读取 https://raw.githubusercontent.com/jweng3/stock-research-reports/main/latest/stocks/AAPL.md 。结合这份报告辅助分析 AAPL，引用实际支撑、阻力及其依据，明确区分报告内容与你的推断；不要给出买卖数量、金额或仓位比例建议。报告可能有误，请主动核验并指出有证据支持的问题。如果链接读取失败或报告过期，请直接说明，不要猜测点位。

最新原文也可直接下载后上传到 ChatGPT。
