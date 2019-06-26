# java-lambda-sample
Lambda (Java) で Kinesis からのイベント処理を行うサンプル (Gradle版) 

## Feature
- Java
- Lambda
- Gradle

## Settings
1. InteliJ IDEA をインストールする。
2. AWS Toolkit for JetBrains をインストールする。
	- Settings > Plugins
3. Docker for Windows をインストールする。
	- Hyper-V の有効化が必要です。
4. AWS SAM CLI をインストールする。
	- Python 3.x が必要です。
5. AWS Console より アクセスキー・シークレットキー を発行する。
	- {ユーザフォルダ}/.aws/credentials に保存する。
```
[default]
aws_access_key_id=xxx
aws_secret_access_key=xxx
```
