# Python 環境建置

## 關於 Python 版本

MacOS 內建 Python 版本為 2.xx，因此要記得使用 `python3` 或 `pip3` 執行指令。
`python3 --version` 確認是否已安裝成功。

## 必要的虛擬環境作業

兩種主要方式：

1. Anaconda
2. Virtualenv

Working Stage | Anaconda | Virtualenv
---------|----------|---------
 安裝套件 | - | `pip3 install virtualenv`
 建立新的虛擬環境 | `conda create --name <ENV_NAME>` | `virtualenv <ENV_NAME>`
 啟動環境 | `conda activate <ENV_NAME>` | `source./<ENV_NAME>/bin/activate`
 退出目前使用的環境 | `conda deactivate` | deactivate
 查看已建置的虛擬環境 | `conda info --en` | -
 刪除虛擬環境 | `conda remove <ENV_NAME> --all` | -

> 若執行 `conda remove <ENV_NAME> --all` 卻未清除乾淨（查看已安裝的環境，仍出現被刪除的虛擬環境），可使用 `conda env remove --name <ENV_NAME>` 指令刪除。

 詳情請見[虛擬環境操作手冊](https://laiyenju.github.io/virtualenv-usage)
