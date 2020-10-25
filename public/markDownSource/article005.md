# Vuetifyの導入方法
## 目的
ブログのデザインをいい感じにしたかった

## 前提
vue.js v2.6.12

vue cli v4.5.6

node  v12.18.4

## 解決方法
Vuetifyを導入することで、簡単にいい感じのデザインにすることができる

## やったこと
**・Vuetifyの導入**

**・公式サイトからソースをコピペまたは参考にする**

### Vuetifyの導入
**vueのプロジェクトを作成**

```
$ vue create project
```

**Vuetifyをインストール**

作成したprojectのフォルダに移動し、以下コマンド

```
$ vue add vuerify
```

以下コマンドで確認すると、以下画像のような画面になります。

```
$ npm run serve
```

<img src="./img/article005/Vuetify.png" decoding="async">

### 公式サイトからソースをコピペまたは参考にする
以下の公式サイトにアクセスします。

<a href="https://vuetifyjs.com/en/" target="_blank">https://vuetifyjs.com/en/</a>

左側のメニューや検索で実装したいコンポーネントを探し、右上の＜＞ボタンからコードを確認、コピペすることができます。

<img src="./img/article005/Vuetify01.png" decoding="async">

私のブログもVuetifyでデザイン等を実装しています。(※2020/09/29時点)

<img src="./img/article005/Vuetify02.png" decoding="async">

以上