# Motion Tool

ブラウザでHumanoidのモーションを作り、UnityのAnimationClip（.anim）として保存するツールです。

https://quikku.github.io/motion-tool/

この公開ページは茜犬だけの見本です。骨を回してキーを打ち、「保存」を押すと、Unityで使える.animができます。ほかのアバターへの対応は想定していません。

作ったモーションは、ブラウザの中で処理するだけで、外部には送信しません。

## 自分のアバターで使う

Unityのスクリプトを使うと、シーンのアバターをこのツールで開けます。

1. [MotionTool.unitypackage](MotionTool.unitypackage)をUnityにインポートします（Unity 2022.3で確認。アバターはHumanoidです）。
2. ヒエラルキーでアバターを選び、`Tools/Motion Tool`を押します。ブラウザでそのアバターが開きます。
3. 骨を回してキーを打ち、「保存」を押します。Assetsの中に.animができます。

既にある.animは、右クリックして`Motion Tool/開く`で開けます。

## クレジット

- 最初に表示されるモデルは[茜犬 -Akane-](https://minto-akayama.booth.pm/items/8861598)です。赤山みんとさんがCC0で公開しています。
- 描画には[three.js](https://threejs.org/)を使っています。ライセンスはMITです。

## ライセンス

CC0です。全文は`LICENSE.txt`にあります。
