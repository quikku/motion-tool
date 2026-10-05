# SisMotionTooL

ブラウザでHumanoidのモーションを作り、UnityのAnimationClip（.anim）として保存するツールです。

https://quikku.github.io/motion-tool/

この公開ページは茜犬だけの見本です。骨を回してキーを打ち、「.anim保存」を押すと、Unityで使える.animができます。ほかのアバターへの対応は想定していません。

作ったモーションは、ブラウザの中で処理するだけで、外部には送信しません。

作りかけはブラウザの中に自動で残り、次に開くと続きから始まります。最初からにするときは「新規」を押します。「プロジェクト保存」で、キーや呼吸の設定をそのまま.sismotionファイルに残せます（.animは呼吸を焼き込むので、開き直しても元のキーには戻りません）。

## 自分のアバターで使う

Unityのスクリプトを使うと、シーンのアバターをこのツールで開けます。

1. [MotionTool.unitypackage](MotionTool.unitypackage)をUnityにインポートします（Unity 2022.3で確認。アバターはHumanoidです）。
2. ヒエラルキーでアバターを選び、`Tools/SisMotionTooL`を押します。ブラウザでそのアバターが開きます。
3. 骨を回してキーを打ち、「.anim保存」を押します。Assetsの中に.animができます。

既にある.animは、右クリックして`SisMotionTooL/開く`で開けます。

## クレジット

- 最初に表示されるモデルは[茜犬 -Akane-](https://minto-akayama.booth.pm/items/8861598)です。赤山みんとさんがCC0で公開しています。
- 描画には[three.js](https://threejs.org/)を使っています。ライセンスはMITです。

## ライセンス

CC0です。全文は`LICENSE.txt`にあります。
