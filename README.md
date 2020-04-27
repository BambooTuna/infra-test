# infra-test

[【備考録】GithubActionsでGECにdocker-composeをデプロイする](https://github.com/BambooTuna/infra-test)の完成品

## 設定すべき環境変数

### GCP関連
- GOOGLE_PROJECT_ID
- GOOGLE_COMPUTE_REGION

    asia-northeast1

- GOOGLE_COMPUTE_ZONE

    asia-northeast1-a

- GOOGLE_SERVICE_KEY

### SSH関連
- SSH_USERNAME
- SSH_KEY
- SSH_KEY_PUB
- SSH_HOST
- SSH_PORT
基本は22だがセキュリティー上変更した方がいい
