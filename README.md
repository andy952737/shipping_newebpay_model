# 藍新金流串接模組 Ruby on Rails 5,6,7 版本
> v1

# 注意重點與說明
透過html將 https://ccore.newebpay.com/MPG/mpg_gateway, MerchantID, Version, TradeInfo, TradeSha送出, 額外搭配自己當下專案的欄位，提示ccore是藍新測試網址，拿掉c是正式。

# 其他注意細節
```

ReturnURL 指 商店欲支付完成後引導消費者回商店網頁
NotifyURL 指 商店欲接收支付完成訊息 
ClientBackURL 指 支付取消返回網址

```