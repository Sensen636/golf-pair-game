# 4人ゴルフ ペアゲーム PWA

## いちばん簡単な公開方法（GitHub Pages）
1. GitHubで新しいリポジトリを作成します。
2. このフォルダ内の5ファイルを全部アップロードします。
   - index.html
   - manifest.json
   - service-worker.js
   - icon-192.png
   - icon-512.png
3. GitHubのリポジトリで Settings → Pages を開きます。
4. Build and deployment の Source を「Deploy from a branch」にします。
5. Branch を「main」、Folder を「/(root)」にして Save。
6. 数分後に表示されるURLをiPhoneのSafariで開きます。
7. Safariの共有ボタン →「ホーム画面に追加」。

## 主な機能
- 4人の名前入力と表ヘッダー自動連動
- 規則モード／任意モード
- 18Hの実スコア入力
- 同点時は過去ホールへ遡って順位決定
- 規則モードで次ホールのペア自動表示
- 任意モードで毎ホールのペア指定
- ペアA得点を入力するとペアBは自動で逆符号
- 4人のゲーム得点累計
- 4人の実スコア合計
- localStorageによる自動保存
- PWA / オフライン対応

## 注意
同じURLでも、入力データは各iPhone端末のブラウザ内に保存されます。
端末間で同じラウンドをリアルタイム共有する機能は入っていません。
