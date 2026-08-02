# Portfolio③：PDF自動生成 + Azure Blob Storage

## 概要

Pythonを使って複数のPDFレポートを自動生成し、Azure Blob Storageに自動保存するシステムです。

## 使用技術

- Python 3.x

- reportlab（PDF生成）

- azure-storage-blob（クラウドストレージ連携）

- Azure Blob Storage

## 処理の流れ

1. データリストを定義

2. reportlabでPDFを自動生成

3. Azure Blob Storageにアップロード

4. ローカルの一時ファイルを削除

## 事前準備

以下の環境変数をWindowsに登録してください。

AZURE_STORAGE_CONNECTION_STRING=接続文字列

## 実行方法

1. 必要ライブラリをインストール

pip install azure-storage-blob reportlab

2. Jupyterで `2603_1_azure_createPDF.ipynb` を開く

3. Kernel → Restart & Run All

## 作者

S_Tasaki