# mhz19c-m5stickc-plus

- MH-Z19C
- M5StickC Plus
- ピン配列変換ケーブル or CO2 HAT

## 繋ぎ方 (ピン配列変換ケーブルを使った場合)

![写真 2022-12-06 23 45 54](https://user-images.githubusercontent.com/1853395/207513356-0292946f-f042-4e91-bb72-baa0973c2fa3.jpg)

## 繋ぎ方 (CO2 HAT を使った場合)

![写真 2022-12-13 19 51 26](https://user-images.githubusercontent.com/1853395/207513685-97f32d9c-ccd8-4729-95bf-3e22e4a845c4.jpg)

### ピン番号

CO2 HAT を使う場合はソースコードのピン番号を変更します

```
#define RX_PIN 36 // Rx pin which the MHZ19 Tx pin is attached to
#define TX_PIN 0 // Tx pin which the MHZ19 Rx pin is attached to
```
