### Ubuntu22.04用のkubernetesクラスタ構築プレイブック
---

Ubuntu22.04用です。kubernetesクラスタを構築します。
python3.10.12で動作を確認。

### Usage


1. inventory.ini.exampleをコピーしてinventory.iniを作成する。
2. intentory.iniのmasterにコントロールプレーンノードのホスト名またはipアドレスを指定する。
3. inventory.iniのnodesにワーカーノードのホスト名またはipアドレスを指定する。
4. プロジェクトルートで ansible-playbook -i inventory.ini playbook.yml を実行する。