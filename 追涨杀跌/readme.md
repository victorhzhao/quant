# 追涨杀跌策略研究

### 美股篇--[追涨杀跌美股.ipynb](追涨杀跌美股.ipynb)针对没有涨跌停限制的股票
 
代码里面Strategy 0对应公众号推送里的策略一，以此类推。

想要测试自己的股票以及修改手续费和比较基准只需要修改第一个cell，比如想要修改成测试Goldman Sachs、比较基准Dow Jones Index、交易收费0.08%只需把以下内容

```python
benchmark = '^GSPC' #(s&p 500) or '^DJI' #(Dow Jones) or '000300.SS' #CSI 300
stock = 'AAPL'
fees = 0
```

改成

```python
benchmark = '^DJI' #(s&p 500) or '^DJI' #(Dow Jones) or '000300.SS' #CSI 300
stock = 'GS'
fees = 0.0008
```

即可


### A股票篇--针对有涨跌停限制的股票 （待更新）