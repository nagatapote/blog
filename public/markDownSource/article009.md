# VueRouter で画面遷移時のスクロール位置制御

## 問題

下にスクロールした状態で、VueRouter で画面遷移した場合に、スクロールされた位置が表示される。

## 前提

vue.js v2.6.12

vue cli v4.5.6

node v12.18.4

## 目的

画面遷移後、必ず画面上部を表示する。

ブラウザバックした場合は、画面上部ではなく、遷移時の位置を表示する。

## 解決方法

router/index.js に以下を追記する。

```javascript
const router = new VueRouter({

〜略〜

  scrollBehavior (to, from, savedPosition) {
    if (savedPosition) {
      return savedPosition
    } else {
      return { x: 0, y: 0 }
    }
  }
})
```

以上
