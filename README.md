# OSRS-JP-transcript
OmegaTプロジェクトのレポジトリです。
OSRSの和訳プラグインのデータを作成するためのプロジェクトになります。

翻訳は自動でアップロード（コミット）されません。
必ず[手動でアップ](#データのアップロード)してください。

*PCのユーザー名が見えてしまうので注意してください。*
## 翻訳の始め方

1. **OmegaTをインストール**:
   - [OmegaT](https://omegat.org/ja/download)を公式サイトからダウンロードしてインストールします。

2. **OmegaTでプロジェクトを開く**:
   1. OmegaTを起動し、メニューの「プロジェクト」から「チームプロジェクトをダウンロード」を選択します。
   ![image2-1](./readme_images/OmegaT%202-1.png)
   2. 「レポジトリ URL」に以下を貼り付けます。

      `https://github.com/YS-jack/YS-jack-OSRS-JP-transcript.git`
   

   3. 「新規ローカルプロジェクトフォルダー」の横の「・・・」ボタンをクリックします。
   ![image2-2](./readme_images/OmegaT%202-2,3.png)
   4. プロジェクトを作成したい場所にして、**フォルダは作成せずに** プロジェクトを入れたいフォルダ名を入力し、「保存」ボタンを押します。
   ![image2-4](./readme_images/OmegaT%202-4.png)
   5. 「確定」ボタンを押します。
   ![image2-5](./readme_images/OmegaT%202-5.png)
   6. プロジェクトがダウンロードされるので少し待ちます。
   7. 画面が変わったら、翻訳作業を開始できます！

3. **翻訳のやり方 - 基本**

    - 中央にあるのが翻訳するデータの一覧になっています。上が元の文章、下が翻訳された文章です。
    - ダブルクリックで翻訳する用語を選択できます。
    - ショートカットキーもいくつかあります。
      - 次の文章に移動 `Ctrl + N`
      - 前の文章に移動 `Ctrl + P`
      - 次の未翻訳の文章に移動 `Ctrl + U`
      - 前の未翻訳の文章に移動 `Ctrl + Shift + U`
    - 右下の「コメント」枠にその文章に関する情報が表示されます。
      - 例えば、dialogueのsourceは発言者名が記載されていて、categoryには会話相手のNPC名が記載されます。（詳しくはWikiにアクセスして確認してください。）
      - Wikiのリンクをクリックすると何やら検索結果が表示されることがあります。その場合は太字になっているページがその文章に関するページです。（裏側事情：直接それを載せるとなると全部で数十時間かかりそうだったので断念しました）
    ![image3](./readme_images/OmegaT%203.png)
4. **用語の登録のお願い**
    
    翻訳を統一させるために、以下のような単語は用語集に登録してください：
    - 他の文章でも使われそうな単語
    - 日常的に使われない特殊な単語
    
    これにより、翻訳が統一され、完成度が上がります。

    **ぜひ積極的に登録してください。**
    
    登録方法は、
    1. 画面右側の`用語集`の枠内で右クリック、`用語の追加`を選択します。

    ![image4-1](./readme_images/OmegaT%204-1.png)

    2. 原文とその翻訳を書き込みます。
    3. コメントとして、どのアイテム・NPC・オブジェクト・会話に出現したかなど必要そうな情報を書いておいてもらえると助かります。

    ![image4-2](./readme_images/OmegaT%204-2.png)

    4. 確定を押せば完了です。用語集の変更は３分に１回チームに共有されます。
5. **複数通りの翻訳**

   もし１つ単語に複数通りの翻訳がある場合、新たな意味として登録したい単語を右クリックし、「例外訳文を登録」を選択してください。

   その後、通常通り翻訳をすると別の同文箇所が自動的に統一されなくなります。

   画像の例：「Title」の訳として現在登録されている「タイトル」とは別の翻訳を登録したい場合は、まず「Title」を右クリックし、「例外訳文を登録」を選択、そして現在の訳と異なる単語を入力する。

   ![image5-1](./readme_images/OmegaT%205-1.png)

## 翻訳後のデータアップロード
終了する前は必ず
 1. メニューの「プロジェクト」を選択
 2. 「訳文ファイルをコミット」を選択

でチームに共有しましょう。

![image_data_commit](./readme_images/OmegaT%20data%20commit.png)

「用語」と「TM」と呼ばれるものはデフォルトで３分に一度チーム全体に共有されます（GitHubにコミットされます）。

ですが翻訳した用語自体は共有されないので上記の方法で訳文を共有してください。

## ログイン情報を求められた場合
もしユーザー名とパスワードを要求された場合は、[管理者](https://discord.gg/DpS9kgxCSJ)に連絡してください。ログイン情報をお伝えします。
   

## 翻訳のルール
   1. 必ず上記の手順でデータをアップロードしてください、翻訳したデータが失われる可能性があります。

   2. 漢字は新聞の常用漢字までにしてください。確認するには先ず[総合漢字チェッカー](http://attosoft.info/tools/kanji-checker/)にアクセスします。
   そして、常用漢字か確認したい漢字を上の記入欄に入力し、「設定」の「新聞常用漢字」を選択したら「チェック」ボタンを押します。すると「チェック結果」に漢字が表示されます。ここで赤くなっていたら常用漢字ではないので、カタカナかひらがなで書きましょう。
      - もし非常用漢字を使用する場合はその文字が表示できるよう漢字の画像を生成する必要があります。
         - 簡単に言うと[RuneLingual Transcript](https://github.com/YS-jack/Runelingual-Transcripts/blob/original-main/README.md)の「updater/char_lists/all_char_ja.txt」にその漢字を書き加え、「updater/update_char_images.py」を実行する必要があります。
      - 詳しくは[連絡](#連絡)よりご相談ください。

<img src="./readme_images/OmegaT%206.png" alt="rule_jouyou_kanji" style="width:450px;"/>


## 原文データの準備・更新

- 詳細なデータの準備方法については、[RuneLingual Transcript](https://github.com/YS-jack/Runelingual-Transcripts/blob/original-main/README.md)をご覧ください。
- もしくは[RuneLingualのDiscord]((https://discord.gg/ehwKcVdBGS))までご連絡ください。
- 必要なのは「.xliff」で終わるファイルなので、このファイル形式のファイルを生成するように上記のプログラムを実行してください。
- XLIFFファイルを入手したら、
   1. 本チームプロジェクトを開く
   2. ファイルエクスプローラーから、生成したXLIFFファイルをプロジェクトフォルダの「sources」のフォルダに入れる
   3. OmegaTの左上より「プロジェクト」＞「原文ファイルをコミット」を押す
   4. OmegaTの左上より「プロジェクト」＞「再読込/リロード」を押す
   4. しばらく待つと、リモート（Gitのサイト側）にアップされて他の人も確認できるようになります。



## 連絡

困ったことがあったら[Discordのルーンスケープ日本語サーバー](https://discord.gg/DpS9kgxCSJ)もしくは[RuneLingualのサーバー]((https://discord.gg/ehwKcVdBGS))で声をかけてください。
