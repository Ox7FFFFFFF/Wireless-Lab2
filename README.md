# Wireless-Lab2
* 實驗環境
    * 硬體版本 : Raspberry Pi 3 Model B+
    * 作業系統 : Raspbian 2018-06-27
    * LoRa : SX1276晶片
* 實驗目標
    * 使用OTAA模式傳輸資料
    * 並用MQTT取得資料後解碼
###### tags: `Wireless`

## OTAA模式送出 (join_ttn.py)
這份程式主要修改來自 [jeroennijhof](https://github.com/jeroennijhof/LoRaWAN) 的程式碼

1. 將程式碼載下來
```shell
$ git clone https://github.com/Ox7FFFFFFF/Wireless-Lab2
```

* 程式資料夾
   * LoRaWAN - 與LoRaWAN相關的程式
   * SX127x - 控制晶片的SPI程式
   * send_ttn.py - 資料送出
   * join_ttn.py - 送出Join封包
   * config.json - Personalized [Dev EUI,AppEUI,AppKey]配置

