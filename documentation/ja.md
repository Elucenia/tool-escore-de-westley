<!-- ELUCENIA technical documentation · escore-de-westley · ja · no clinical/professional/rights approval -->

# Westleyスコア（クループ）

[条件・出典・許諾](https://elucenia.org/ja/tools/escore-de-westley)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### 意識レベル

`cons`

- `0` — 正常（睡眠中を含む）
- `5` — 見当識障害

### チアノーゼ

`cian`

- `0` — なし
- `4` — 興奮あり
- `5` — 安静時

### 吸気性喘鳴

`estr`

- `0` — なし
- `1` — 興奮あり
- `2` — 安静時

### 空気の流入

`ar`

- `0` — 正常
- `1` — 低下
- `2` — 著しく低下

### 陥没呼吸

`ret`

- `0` — なし
- `1` — 軽度
- `2` — 中等度
- `3` — 重度

## 方法の版

Westley 1978：5因子，0–17；クループ

## 記載された計算式

5項目を合計：意識（0または5），チアノーゼ（0，4または5），吸気性喘鳴（0～2），空気流入（0～2），陥没呼吸（0～3）。合計0～17。

## 限界・対象集団

Westley 1978の論文は介入試験で、急性クループにより入院し、安静時にも持続する吸気性喘鳴のあった4か月から5歳の小児20人を評価しました。この年齢範囲は原コホートの記述であり、それだけでスコア使用の普遍的な範囲は定まりません。採用する採点表と重症度分類は個別に確認する必要があります。

## 参考文献

- [Westley CR, Cotton EK, Brooks JG. Nebulized racemic epinephrine by IPPB for the treatment of croup: a double-blind study. Am J Dis Child, 1978.](https://doi.org/10.1001/archpedi.1978.02120300044008)

- [Bjornson CL, Johnson DW. Croup in children. CMAJ, 2013.](https://doi.org/10.1503/cmaj.121645)

## 技術テストの再現

このリポジトリのルートディレクトリでnode test.cjsを実行すると、記録された合成ケースを再実行できます。元の入力、期待結果、許容誤差は保持されています。技術テストは臨床的検証を意味しません。

```sh
node test.cjs
```

tool.jsonには出典、版、確認範囲が記録されています。examples.jsonには合成入力と期待結果が保持され、results.jsonには実際に得られた結果が記録されています。

[記録・参考文献](../tool.json) · [JavaScriptコード](../calculator.js) · [参照ケース](../examples.json) · [results.json](../results.json)

## 確認状況と使用条件

独立した臨床レビューは実施されていません。

このインターフェースは独自に作成した翻訳であり、公式版や認証済みの版ではありません。独立した臨床レビュー、専門家による言語レビュー、評価尺度等の権利許諾の確認は実施されていません。

式または分類の結果です。解釈、対応、適用可能性は専門家による評価と選択した出典に依存します。

## ライセンスと帰属表示

Apache-2.0はELUCENIAのコードにのみ適用されます。評価尺度等、出版物、翻訳、データの権利は、それぞれの権利者に帰属します。LICENSEとNOTICEを保持してください。

ELUCENIA · Felipe Guedes · Copyright © 2026
