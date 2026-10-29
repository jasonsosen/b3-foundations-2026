# 曹研究室 B3基礎教育

[授業一覧](https://jasonsosen.github.io/b3-foundations-2026/)

全15回、各180分の授業です。

| 回 | 授業資料 |
|---|---|
| 第1回 | [ガイダンス・ColabとPython](lessons/01/) / [PDF](materials/01/slides.pdf) |
| 第2回 | [TerminalでPythonを実行する](lessons/02/) / [PDF](materials/02/slides.pdf) |
| 第3回 | [シミュレーションとMuJoCo](lessons/03/) / [PDF](materials/03/slides.pdf) / [Notebook](materials/03/notebook.ipynb) |
| 第4回 | [台車・振子モデルと振子の同定](lessons/04/) / [A Notebook](materials/04/model.ipynb) / [B Notebook](materials/04/identification.ipynb) |
| 第5〜15回 | 工事中 |

第1〜3回の各ページにPDFとColab実習のリンクを掲載しています。第5〜15回は工事中です。第3回Notebookは独立実行できる2冊に分かれます。

- A 小球篇：Euler/RK4、MuJoCoの小球・接触・関節、Terminal、横向き運動・抵抗。
- B 2リンクロボット篇：各小節の6段階の流れ図、モデル作成、姿勢、トルクによる運動、倒立振子への接続。

AからBへのファイル転送や、実行状態の引き継ぎは不要です。全課題は必修。初見で2冊を180分以内に終える想定ではありません。PDFは従来版v6、実習手順は各Notebookを使います。

第1・2回のColabは元のGoogle Drive教材を開きます。共有範囲は「リンクを知っている全員」、権限は「閲覧者」です。実行・保存するときはGoogleアカウントでログインし、自分のDriveへコピーしてください。

- [第1回 Colab](https://colab.research.google.com/drive/1ZdDFFNfeDRK4dEzME4E3wEAp5zHElpoN?usp=sharing)
- [第2回 Colab](https://colab.research.google.com/drive/1m3ff0OOlyYH0OrJ8MMpPL3AChTdIDqF0?usp=sharing)

- [第3回A 小球 Colab](https://colab.research.google.com/github/jasonsosen/b3-foundations-2026/blob/main/materials/03/ball.ipynb)
- [第3回B 2リンク Colab](https://colab.research.google.com/github/jasonsosen/b3-foundations-2026/blob/main/materials/03/two_link_robot.ipynb)

第3回はこのリポジトリの学生用NotebookをColabで直接開きます。旧notebook.ipynbは小球篇と同一の互換入口です。ファイルの手動アップロードは不要です。実行・回答の保存には自分のDriveへコピーしてください。

GitHub Pagesはmainブランチのルートを公開します。

第3回の課題は翌週のPPT発表で報告します。ZIP・CSV・Notebookの提出は不要です。Notebookは自分用の実験記録としてDriveに保存し、発表では自作コード・図や数値・結果の理由を説明します。

第4回は、Aで台車・振子モデルを作り、Bで配布プログラムを実行してシステム同定の式と計算を理解します。次回は各自でAのモデル・実行の流れ・運動結果をPPTで発表します（必須）。Bの実習と、式を用いたシステム同定の説明は任意の加点項目です。
