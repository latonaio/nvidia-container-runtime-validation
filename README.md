# nvidia-container-runtime-validation
nvidia-container-runtime-validation は、NVIDIAコンテナランタイムの有効化手順を示したレポジトリです。  

## 動作環境

* NVIDIA サーバーまたは NVIDIA Jetson

## NVIDIAコンテナランタイム有効化手順
NVIDIAコンテナランタイムの有効化手順として、次の操作を実行してください。  

* [Docker 公式リポジトリ](https://docs.docker.com/engine/install/ubuntu/)から最新版の Docker をインストールしてください。
* `/etc/docker/daemon.json` に `"default-runtime": "nvidia"` を追加し、Docker を再起動してください。