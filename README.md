# 開発日記

## 目的
- 柔軟に使えるマッチングアルゴリズムを作りたい

## アルゴリズムの要件
1. 安定マッチングが計算できる
2. グループの人数が同じでない集団同士のマッチもできる
3. グループ問わず特定の人の希望を優先できる

## 日誌
### ?/? 始動
### 2025/3/11
- Gale_Shaplayアルゴリズムの実装、brute_forceな探索アルゴリズムの実装が完了
- Gale_Shaplayアルゴリズムでは、brute_forceで探した最適なマッチングが探索できることを確認した
- 安定マッチングにならないケースを何回か実験をして探してみたが、あまり実現できていない。安定マッチングは結構実現可能なのかも。