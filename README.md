# WhisperGUI

![pic](https://user-images.githubusercontent.com/106337749/221340883-4b437d03-97fc-42ee-821e-dd04096323fe.png)

> このプロジェクトは、私が2時間で簡単に作成したWhisperGUI+クイックインストールパッケージです。これにより、Whisperを使用する際に迅速に操作でき、コマンドを入力する必要がなく、手動で多くのものをインストールするのが面倒な人々が迅速に使用できるようになります（PythonおよびFFmpegは自分でインストールする必要があります）。

> 2023.03.30更新 最近、GPUを検出できないという報告がありました。現在、CUDA Toolkitに関連している可能性があると推測しています。CUDA Toolkitをインストールしていない場合は、まずNvidia CUDA Toolkitをインストールしてみてください。インストールしてもGPUが表示されない場合は、Batファイルの22行目を調整し、インストールされているTorch CUDAバージョンをコンピュータのCUDA Toolkitバージョンと一致させてみてください。

> 2023.08.12更新 現在、このプロジェクトを実行ファイルにパッケージ化するテストを行っています。setup.batを実行して仮想環境を作成する必要はなく、ダウンロードして解凍し、**main.exe**を実行するだけで実行できます。リリースページからダウンロードして試してみてください。（パッケージ版は、手動でCUDA Toolkitをインストールする必要はありません）

[OpenAI Whisper](https://github.com/openai/whisper)

## プロジェクトの目的

このプロジェクトの目的は、Whisperの実行環境を迅速に設定できるようにすることです。

また、多くのユーザーがこのGUIインターフェースを通じて操作できるようにし、コマンドを入力する必要がないようにすることです。

## 機能

現在、以下のWhisperの機能をサポートしています。
1. 複数の音声ファイルを選択
1. 出力場所を選択
1. 使用モデルを選択
1. 認識言語を選択
1. 使用デバイスを選択（CPU、指定されたGPU）
1. 字幕を英語に翻訳

## 画面

> 操作例：ファイルを選択 > モデルを選択 > 実行完了

![選模型](https://user-images.githubusercontent.com/106337749/218459288-0fd24ee4-4ed6-49c9-a3f4-1fd97976a89d.png)
![選装置](https://user-images.githubusercontent.com/106337749/218459323-faaf2d8d-0a68-4bfc-a6e3-62e45b94ad0f.png)
![執行完成](https://user-images.githubusercontent.com/106337749/218460468-a801fe68-0f01-479d-a4bd-4f04eea1af41.png)

## インストール

> まず、Python 3.7以上のバージョンとFFmpegをインストールしてください。

以下は、このプロジェクトをコンピュータで実行する方法を説明します。

### プロジェクトの取得

```bash
git clone git@github.com/ADT109119/WhisperGUI.git
```

**または、GitHubページで「Download ZIP」をクリックしてください。**

### PythonおよびFFmpegがインストールされていることを確認

```bash
python --version
ffmpeg -version
```

### setup.batを実行

フォルダ内のsetup.batを実行し、仮想環境のセットアップが完了するのを待ちます。

### プロジェクトを実行

フォルダ内のrun.batを実行してください。エラーがなければ、GUIインターフェースが表示されます。

## フォルダの説明

- model - モデルの保存場所
- output - デフォルトの出力フォルダ
- venv - 仮想環境フォルダ
...

## プロジェクト技術

- Python
- tkinter
- ttkbootstrap

## 作者に連絡

以下の方法で私に連絡できます

- [Email: 2.jerry32262686@gmail.com](mailto:2.jerry32262686@gmail.com)
...

## License
This project is under the MIT License. See [LICENSE](https://github.com/ADT109119/WhisperGUI/blob/main/LICENSE) for further details.
