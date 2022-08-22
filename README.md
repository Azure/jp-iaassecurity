# Azure インフラストラクチャ:ガバナンス強化とセキュリティ対策ガイド
本ドキュメントでは、Azure 仮想マシンを中心としたワークロードを安全に運用するために、運用モデルの考え方(ランディングゾーン、ハブアンドスポークトポロジ)と活用できるサービス ( Azure Firewall 、Defender for Cloud ) について紹介しています。ここで取り上げた製品・サービスの詳細および最新情報は、[製品ドキュメント](https://docs.microsoft.com)をご参照ください。なお、本ドキュメントの作成には、[BIPROGY株式会社](https://www.biprogy.com/)様にご協力をいただきました。

## [はじめに](./chapter00.md)
## [1章 ランディングゾーン](./chapter01.md)
ランディングゾーンは、個人情報保護や、情報流出を未然に防ぐために企業ごとに存在し、時代の変化に応じて変化していくポリシーに柔軟に対応するために、有効的なアーキテクチャです。
## [2章 ハブアンドスポークネットワークトポロジ](./chapter02.md)
ハブアンドスポークは、一般的な通信またはセキュリティ要件を効率的に管理するためのネットワーク モデルです。 Azure サブスクリプションの制限の回避にも役立ちます。
## [3章 Azure Firewall](./chapter03.md)
Azure Firewall は Azure で実行されているワークロードを保護するクラウドネイティブなファイアウォールです。
## [4章 Azure 内のサーバを保護する - Microsoft Defender for Servers](./chapter04.md)
Microsoft Defender for Servers は、Azure だけでなく、AWS 、GCP 、オンプレミスといった Azure 以外で実行している Windows マシンと Linux マシンに脅威検出と高度な防御を追加することを可能とする Azure 上のサービスです。

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
