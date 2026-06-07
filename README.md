# Tatsuo Indo

## 👨‍💻 About Me

36年程の**プログラマ／インフラエンジニア**としての経験を持ちます。
最近の10～20年程は、Oracle Database（RAC）構築・維持保守、Unix/Linux サーバー構築を軸に、Python・Shell・PowerShell によるスクリプト開発を手がけてきました。
近年はクラウド（AWS）へのシフトを進めています。

---

## 🛠️ Skills

| カテゴリ | 技術・製品 |
|---------|-----------|
| **OS** | Linux (RHEL,Debian), Solaris, HP-UX, Windows Server |
| **DB** | Oracle (19c, 18c, 11g, 10g, 8i, 8) / Oracle RAC |
| **言語** | Python, Shell (bash,csh), PL/SQL, Perl, PowerShell, Pro*C, COBOL, VBScript, JScript, Ruby, VBA |
| **クラウド** | AWS (S3, Lambda, EC2) |
| **インフラ** | Oracle Database 設計・構築, Unix/Linux サーバー構築|
| **仮想化** | VMware ESXi |
| **その他** | Raspberry Pi, Ansible (inventory管理) |

---

## 🏆 Certifications

- **AWS Certified Cloud Practitioner** (2026/02)

---

## 📂 Portfolio

### [run_on_ec2_public](https://github.com/indouxp/run_on_ec2_public)
> S3イベント連携によるEC2自動処理システム

- S3へのファイルアップロードを契機に Lambda が EC2 を動的起動し、バッチ処理を自動実行するイベント駆動型システム
- 処理完了後は EC2 を自動削除し、SNS/SES でメール・SMS 通知
- インフラ構築をシェルスクリプトでコード化（IaC）
- 要件定義書・基本設計書・セキュリティ設定書・運用手順書など設計ドキュメント一式を整備

**技術スタック：** AWS (S3, Lambda, EC2, SNS, SES, EventBridge, IAM, VPC) / Python / Shell (bash)

---

### [security_monitor_2_public](https://github.com/indouxp/security_monitor_2_public)
> 自宅LAN向け マルチカメラ セキュリティモニターシステム

- AtomCam 3台の RTSP ストリームを WebRTC (WHEP) でブラウザに集約表示（2×2グリッド）
- Raspberry Pi 4 上で MediaMTX・nginx・coturn・メトリクス収集デーモンが稼働
- CPU使用率・温度・ディスクI/O・メモリのリアルタイムグラフ表示
- Shell・Python・JavaScript・PowerShell の複合構成
- 単体テスト（Shell/Python/PowerShell）・結合テスト（Playwright）を実装

**技術スタック：** Python / Shell (bash) / JavaScript / PowerShell / MediaMTX / WebRTC / nginx / Raspberry Pi OS

---

## 📈 Career Summary

| 期間 | 内容 |
|------|------|
| 2022 - 2024 | 共済システム：Oracle RAC 19c 構築（RHEL 8.6 / VMware）、AWS S3 環境構築、Python/Bash によるメール配信システム開発 |
| 2019 - 2020 | 共済システム：Oracle RAC 18c 構築（Windows Server 2016 / VMware） |
| 2016 - 2018 | 共済システム：Oracle RAC 11g 構築（Windows Server 2012 / VMware） |
| 2014 - 2016 | 共済システム：LDAP 個人データ反映（PowerShell / Bash） |
| 2012 - 2013 | 生保システム：Oracle DB 10g/11g 維持保守（Solaris 10/11） |
| 2001 - 2011 | 金融（生保・共済・損保・証券）：Oracle 8,8i,9i 環境構築・維持保守、ジョブ管理開発（HP-UX / Solaris / Windows Server） |
| 1994 - 2001 | 会計システム開発・保守（HP-UX / Oracle Forms / Pro*C / Shell） |
| 1988 - 1994 | 金融系（住宅ローン・カードローン）システム開発（MVS / DOS/VSE / COBOL） |

---

## 💡 Strengths

- **Oracle RAC の専門知識** — 8・8i・10g・11g・18c・19c の設計・構築・維持保守
- **インフラ × スクリプト開発の複合スキル** — サーバー構築とバッチ処理・データ連携開発を一体で担当
- **AWS へのシフト** — クラウド実装経験（S3, Lambda, EC2, SNS/SES）と資格を保有
- **ドキュメント整備** — 要件定義・基本設計・詳細設計・テスト仕様・運用手順書の一式作成

---

## 📫 Contact

- GitHub: [@indouxp](https://github.com/indouxp)
