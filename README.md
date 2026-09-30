# 曹研究室 B3基礎教育

[教材サイトを開く](https://jasonsosen.github.io/b3-foundations-2026/)

機械系B3向けの反転学習教材。各回180分。例を読む → 予想 → 一つ変更 → 実行・確認 → 自分の言葉で説明する、という手順で進めます。

| 回 | 内容 | Colab | スライド | Notebook |
|---|---|---|---|---|
| 第1回 | ガイダンス・Colab・Python・ベクトルと行列 | [開く](https://colab.research.google.com/github/jasonsosen/b3-foundations-2026/blob/main/materials/01/notebook.ipynb) | [PDF](materials/01/slides.pdf) / [PPTX](materials/01/slides.pptx) | [主教材](materials/01/notebook.ipynb) |
| 第2回 | Terminal・Pythonスクリプト・エラー診断・コンパイル | [開く](https://colab.research.google.com/github/jasonsosen/b3-foundations-2026/blob/main/materials/02/notebook.ipynb) | [PDF](materials/02/slides.pdf) / [PPTX](materials/02/slides.pptx) | [主教材](materials/02/notebook.ipynb) |

第1回の[Python・行列参考本をColabで開く](https://colab.research.google.com/github/jasonsosen/b3-foundations-2026/blob/main/materials/01/python-matrix-reference.ipynb)。参照用なので第1回ですべて終える必要はありません。

## 使い方

1. Colabで開き、自分のGoogle Driveへコピーします。
2. 説明を読み、確認問題の予想を書いてから実行します。
3. 実際の結果、変更点、理由をNotebookへ記録します。
4. 必要なNotebook・.py・図・CSVを保存して提出します。

第1・2回はPPT発表なし。第2回のTerminal命令は実際のColab Terminalに入力してください。Notebookの「すべて実行」ではTerminal課題は実施されません。

## 元のDrive版

- [第1回](https://colab.research.google.com/drive/1ZdDFFNfeDRK4dEzME4E3wEAp5zHElpoN)
- [第2回](https://colab.research.google.com/drive/1m3ff0OOlyYH0OrJ8MMpPL3AChTdIDqF0)
- [リンク一覧](materials/links.json)

## 配布版

- 第1回PPT：2026-09-24 v2、29ページ。学生Notebook・参考本：2026-09-25。
- 第2回PPT・Notebook：2026-09-30改訂、12ページ。
- [第1回ZIP](materials/lesson-01.zip) / [第2回ZIP](materials/lesson-02.zip)
- 元教材の内容は変更せず、配布ファイル名だけを統一しています。[ファイルハッシュ](materials/manifest.json)

## サイトの更新

HTMLとCSSだけの静的サイトです。GitHub Pagesはmainブランチのルートを公開します。教材を更新するときは、materials内のPPTX・PDF・NotebookとZIP、manifest.json、ページの版表示をそろえて更新してください。

ローカルで確認する場合は、このフォルダで `python -m http.server 8000` を実行し、http://localhost:8000 を開きます。
