# WhisperGUI

![pic](https://user-images.githubusercontent.com/106337749/215111798-2efbd62e-95d9-4bfa-ae52-653896bd3f4f.jpg)

> 此專案是我用2個小時簡單製作的WhisperGUI+快速安裝包，可以讓我們在使用Whisper時快速操作，無須打指令，以及讓懶得手動裝一堆東西的人可以快速的使用(Python以及FFmpeg還是要自己裝)。

[OpenAI Whisper](https://github.com/openai/whisper)

## 專案用途

此專案的作用

在於方便大家可以快速設定好的Whisper執行環境

以及讓多數使用者

可以僅需透過此GUI介面操作使用

而無須打指令


## 功能

目前支援操作以下幾種Whisper的功能
1. 選擇音檔
1. 選擇輸出資料夾
1. 選擇使用模型
1. 選擇辨識語言
1. 選擇使用裝置(CPU、指定顯卡)
1. 將字幕翻為英文


## 畫面

> 操作示意 選擇檔案>選擇跑模型的裝置>執行完成

![選模型](https://user-images.githubusercontent.com/106337749/215115914-0392e62d-bc41-4694-8b63-01002bf68af4.jpg)
![選裝置](https://user-images.githubusercontent.com/106337749/215116002-ac2e988c-f0bd-4a25-ac6c-8ec71a3de37f.jpg)
![執行完成](https://user-images.githubusercontent.com/106337749/215116019-61405444-e634-4640-b62e-9dcd97cc63df.jpg)

## 安裝

> 請先自行安裝Python 3.7以上版本，以及FFmpeg

以下將會引導你如何在你的電腦上執行此專案。

### 取得專案

```bash
git clone git@github.com/ADT109119/WhisperGUI.git
```

**或是直接在GitHub頁面點Download ZIP**

### 確認電腦已有Pyhton以及FFmpeg

```bash
python --version
ffmpeg -version
```

### 執行setup.bat

請直接執行資料夾中的setup.bat，等待虛擬環境完成設置

### 執行專案

請直接執行資料夾中的run.bat，若無報錯，將可以看到GUI介面

## 資料夾說明

- model - 模型存放處
- output - 預設輸出資料夾
- venv - 虛擬環境資料夾
...

## 專案技術

- Python
- tkinter

## 聯絡作者

你可以透過以下方式與我聯絡

- [Email: 2.jerry32262686@gmail.com](mailto:2.jerry32262686@gmail.com)
...

## License
This project is under the MIT License. See [LICENSE](https://github.com/ADT109119/WhisperGUI/blob/main/LICENSE) for further details.