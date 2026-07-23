# Tatsuo Indo

## 👨‍💻 About Me

金融系システムを中心に、サーバー構築からスクリプト開発まで、「作る、安定させる」エンジニアとして歩んできました。Oracle、RAC・Unix/Linuxの構築と、Python・Shell・Perl・PowerShellによる自動化・運用改善を並行して手がけてきました。これらの経験を、クラウド環境の構築・開発に活かしていきたいと考えています。<br>
[![AWS Certified Cloud Practitioner](https://images.credly.com/size/150x150/images/00634f82-b07f-4bbd-a6bb-53de397fc3a6/image.png)](https://www.credly.com/badges/28b2e916-ea74-494f-83b4-eca8d3d1b612/public_url)
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

## 🏆 Certifications

- **AWS Certified Cloud Practitioner** (2026/02)

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

## 📈 Career Summary

| 期間 | 内容 |
|------|------|
| 2021 - 2024 | 金融・共済 ：査定エンジン、メール配信 Oracle RAC 19c 構築（RHEL 8.6 / VMware）、AWS S3 環境構築、Python/Bash によるメール配信システム開発 |
| 2019 - 2020 | 金融・共済 ：開発フレームワーク Oracle RAC 18c 構築（Windows Server 2016 / VMware） |
| 2016 - 2018 | 金融・共済 ：PG支援 Oracle RAC 11g 構築（Windows Server 2012 / VMware） |
| 2014 - 2016 | 金融・共済 ：PG支援 LDAP 個人データ反映（PowerShell / Bash） |
| 2012 - 2013 | 金融・生保 ：団体保険 Oracle DB 10g/11g 維持保守（Solaris 10/11） |
| 2001 - 2011 | 金融（生保・損保・証券）：Oracle 8,8i,9i 構築・維持保守、ジョブ開発（HP-UX / Solaris / Windows Server） |
| 1994 - 2001 | 流通小売・：統合会計システム(給与) 開発・保守（HP-UX / Oracle Forms / Pro*C / Shell） |
| 1988 - 1994 | 金融（信販（クレジット）・消費者金融）システム開発（MVS / DOS/VSE / COBOL） |

---

## 💡 Strengths

- **Oracle, RAC の知識** — 8・8i・10g・11g・18c・19c の設計・構築・維持保守
- **インフラ × スクリプト開発の複合スキル** — サーバー構築とバッチ処理・データ連携開発を一体で担当
- **AWS へのシフト** — クラウド実装経験（S3, Lambda, EC2, SNS/SES）と資格を保有
- **ドキュメント整備** — 要件定義・基本設計・詳細設計・テスト仕様・運用手順書の一式作成

---

## 📫 Contact

- GitHub: [@indouxp](https://github.com/indouxp)
