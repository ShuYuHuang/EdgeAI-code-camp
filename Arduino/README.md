# EdgeAI自走車 Arduino 控制程序

## 前置需求
1. Arduino IDE 安裝([連結](https://www.arduino.cc/en/main/software))
2. 安裝Git bash([連結](https://gitforwindows.org/))
  - Linux: sudo apt-get install git-all

## 操作流程
首先要從Arduino程序從git repo拉下來:
```
cd <指定路徑>
git pull https://gitlab.aiacademy.tw/junew/EdgeAI_code_temp.git
```

接下來打開Arduino資料夾，使用Arduino IDE打開`car.ino`

連接到UNO板上，編譯.ino程式碼然後進行燒錄。

完成後自走車就會開始移動了。