# 第4回課題

## VPC・サブネットの構築

* VPC作成

![VPC](images/vpc.png)

* サブネット **private1**

![サブネット1](images/subnet_pri1.png)

* サブネット **private2**

![サブネット2](images/subnet_pri2.png)

* サブネット **public1**

![サブネット3](images/subnet_pub1.png)

* サブネット **public2**

![サブネット4](images/subnet_pub2.png)


## EC2インスタンスの作成

![EC2インスタンス](images/ec2instance.png)

## EC2のセキュリティグループ

* インバウンド (修正済み)

![EC2インバウンド](images/ec2inbound_modify.png)　

* アウトバウンド

![EC2アウトバウンド](images/ec2outbound.png)

## RDSの作成　(要修正)

![RDSの作成](images/rds_db.png)

## RDSのセキュリティグループ

* インバウンド (要修正)

![RDSインバウンド](images/rdsinbound.png)

* アウトバウンド

![RDSアウトバウンド](images/rdsoutbound.png)

## Teratermを用いたEC2へのSSH接続及びECからRDSへ接続

![SSH接続](images/ec2ssh.png)

## 感想

* 秘密鍵の取り扱いには気を付けること、絶対に外部に流出刺せないことを心がける。
* また費用をできるだけ抑えるために、サインアウトの際は必ずEC2を停止する。
* 回を重ねるたびに知らない用語が増えていくので身につくように、また説明できるように勉強します。