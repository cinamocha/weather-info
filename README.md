# 天気情報アプリ(weather-info)  
天気情報を取得して表示するPythonアプリ。OpenWeatherMap APIを使って、指定した都市の天気を取得し、表示します。

## ファイル構成  
- **tenki.py**:天気と気温を出力できます。
- **tenki2.py**:見やすく改良し、湿度、風速も出力できるようになりました。
- **tenki_gui.py**:Tkinterを使用し、デスクトップアプリになりました。

## 使い方  
1. **APIキーの取得**  
   OpenWeatherMapからAPIキーを取得し、`API Keyを入力`に入力してください。

2. **ライブラリのインストール**
```
pip install requests
```

3. **実行**
```
python tenki.py
python tenki2.py
python tenki_gui.py
```

## スクリーンショット  
![tenki.py](https://github.com/cinamocha/weather-info/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202024-12-08%20131659.png)  
![tenki2.py](https://github.com/cinamocha/weather-info/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202024-12-08%20131731.png)  
![tenki_gui.py](https://github.com/cinamocha/weather-info/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202024-12-08%20132037.png)
