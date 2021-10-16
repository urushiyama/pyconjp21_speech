# Pythonでつくる宣言的UIラッパーフレームワーク〜既存GUIフレームワークの調査を添えて

## やったこと

- Pythonを用いた仮想DOMの実装

## スライド

<iframe class="speakerdeck-iframe" frameborder="0" src="https://speakerdeck.com/player/dbba5ada78564537891f8170298bc2ed" title="Pythonでつくる宣言的UIラッパーフレームワーク〜既存GUIフレームワークの調査を添えて" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true" style="border: 0px; background-color: rgba(0, 0, 0, 0.1); margin: 0px; padding: 0px; border-top-left-radius: 6px; border-top-right-radius: 6px; border-bottom-right-radius: 6px; border-bottom-left-radius: 6px; -webkit-background-clip: padding-box; -webkit-box-shadow: rgba(0, 0, 0, 0.2) 0px 5px 40px; box-shadow: rgba(0, 0, 0, 0.2) 0px 5px 40px; width: 560px; height: 314px;"></iframe>

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
