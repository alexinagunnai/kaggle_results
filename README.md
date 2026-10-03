# Kaggle competition results

コンペで取り組んだ手法、検証結果、学びと再現用コードを保存する repository です。

成果は `competitions/<slug>/` にまとめます。

- `README.md`: 目標、手法、主要な試行、CV / Public LB / Private LB、学び、再現手順
- `src/`、`notebooks/`、`config/`: コンペ固有のコードと設定
- `requirements.txt` または `pyproject.toml` / `uv.lock`: コンペの実行環境
- `results/`: 公開する指標、図表、小さい結果ファイル

開発用 workbench は隣の `kaggle_runner` にあります。成果を選んでコピーし、差分を確認してから commit / push します。データ、モデル本体、秘密情報、大量のログは保存しません。notebook の出力も公開前に確認してください。

この repo は成果の閲覧と再現用です。KLW workspace の完全な復元用ではありません。
