👋 Hi there, I'm nakagawa_PK

Welcome to my GitHub profile! I am a developer passionate about building tools that solve real-world problems with a strong focus on User Experience (UX) and clean code.

🚀 Highlighted Project: リアルタイム旅行精算システム (Travel Expense Splitter)

身内や友人との旅行で発生する「面倒なお金のやり取り」を極限までスムーズにする、LINE LIFFを活用したWebアプリケーションです。

💡 なぜ作ったのか？ (The Problem)

旅行中の精算には「その場でサクッと割りたい」「最後にまとめて計算したい」「各自が随時入力したい」という複数のニーズがあります。しかし、既存のアプリでは機能が複雑すぎたり、逆にシンプルすぎてETCやガソリン代の計算が手作業になったりしていました。

✨ どう解決したか？ (The Solution)

ユーザーの「利用シーン」に合わせて3つのモードを用意し、別アプリを開く手間を省くための独自機能（ミニ電卓、GPS連動の経路検索）をアプリ内に統合しました。

🚗 簡易精算: 登録不要。その場ですぐに合計を等分できるモード。

📊 詳細精算: 旅行の最後に代表者がレシートをまとめて入力し、自動で最適な送金ルートを計算するモード。

⏱️ リアルタイム精算: 参加者が各自のスマホから同時にアクセスし、立替履歴をリアルタイムで共有・保存できるモード。

🛠️ こだわりの機能・UX (Key Features)

特に見ていただきたいのは「UX改善のプロセス」です。

アプリ間の移動をゼロにする「ミニ電卓」の統合

課題: ドライブ旅行の最後に「ETCの履歴を車載器に読み上げさせ、スマホの電卓で合算して入力する」というユーザー行動がありました。

解決: 入力画面内にサッと引き出せる「専用ミニ電卓」を実装。数字と「＋次へ」を連続でタップするだけで完結するUIにより、アプリの行き来やキーボード切り替えのストレスを完全に排除しました。

GPS × Google Maps API 連動のガソリン代自動計算

課題: ガソリン代の精算時、走行距離を調べるために別でマップアプリを開く必要がありました。

解決: GAS(Google Apps Script)のMapsサービスを活用し、現在地のGPS座標と目的地を入力するだけで、最適ルートの距離(km)を自動算出して入力欄に反映する機能を実装しました。

「無限湧き出し」方式による入力のシンプル化

課題: 簡易精算画面で、入力項目が多い場合に最初から沢山のテキストボックスを表示すると、ユーザーが圧倒されてしまいます。

解決: 最後の行を入力した瞬間に、次の入力行がアニメーション付きでフワッと現れるUIを実装。見た目のシンプルさと拡張性を両立しました。

💻 技術スタック (Tech Stack)

Frontend: HTML5, CSS3, JavaScript, Bootstrap 5.3, LINE LIFF (v2)

Backend: Google Apps Script (GAS)

Database: Google SpreadSheet

🛠️ Skills & Tools

🌱 GitHub Stats
