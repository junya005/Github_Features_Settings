# Github_Features_Settings
Githubの機能 ( Issue, Action等 ) を使う際のテンプレートや設定ファイルを個人用にまとめています。

## Unityの自動ビルド

使用手順
1. `.github/workflows/`にある`build-unity.yml`を同じように配置します。
2. ファイル内の`on:`の記述を変更することで任意のトリガーを設定できます。
3. リポジトリの`seacrets`に`UNITY_EMAIL`と`UNITY_PASSWORD`と`UNITY_LICENSE`を設定してください。
   ※`UNITY_EMAIL`と`UNITY_PASSWORD`はUnityのログイン情報、`UNITY_LICENSE`はUnityのライセンスファイルの中身を設定します。
