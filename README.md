# Pythonでつくる宣言的UIラッパーフレームワーク〜既存GUIフレームワークの調査を添えて

## やったこと

- Pythonを用いた仮想DOMの実装

## 伝えたかったこと

- `__new__` を実装することで、クラスを用いる `with` ステートメントでの挙動をハックできること

## スライド

- [SpeakerDeck](https://speakerdeck.com/urushiyama/pythondetukuruxuan-yan-de-uiratupahuremuwaku-ji-cun-guihuremuwakufalsediao-cha-wotian-ete)
- [Keynote](/slide/YutaUrushiyama_PyConJP21.key)
- [PDF](/slide/YutaUrushiyama_PyConJP21.pdf)

## 成果物

- [DeUI-Kitchen](https://github.com/urushiyama/DeUI-Kitchen)
    - [DeUI](https://github.com/urushiyama/DeUI)
        - コアロジックとHTMLラッパーの実装
    - deui-dev/[reloadrable](https://github.com/urushiyama/reloadrable)
        - 開発時に必要なライブラリ
        - deui-examples/[flask](https://github.com/urushiyama/deui-examples-flask) で利用
    - deui-examples/[flask](https://github.com/urushiyama/deui-examples-flask)
        - HTMLラッパーを用いたFlaskアプリの実行例

- [アスペクト指向な `with statement` によるコンテクスト束縛](https://gist.github.com/urushiyama/c950f641e884c29ae9866dbadbf3dcc6)
