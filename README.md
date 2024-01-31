## 此 Repo 的目標
====
將線上找到幾個極光背景效果 (aurora gradient background) 實作方式整理出來，由 `linear-gradient()` (線性漸層) 或 `radial-gradient()` (圓形漸層) 配合上 `filter: blur();` 產生，接著以 CSS 動畫方式產生迴圈動畫。


## 參考資料
====
- [Elevate Your Website with Radial Gradient Background | HTML & CSS Only |](https://www.youtube.com/watch?v=RohGByqWD_E)
  - 說明：
    1. radial-gradient() 設定原理
    2. 在元素內的定位關係
    3. 最後層元素背景色使用
    4. 未整合 CSS 動畫
- [CSS Morphing Gradients Animated Background](https://www.youtube.com/watch?v=Ml-B-W91gtw)、[GitHub Link](https://github.com/baunov/gradients-bg)
  - 說明：
    1. 純 CSS 整合動畫樣式
    2. 簡單的頁面結構與導航列組成

- [Animated Aurora Gradient Background with CSS -Build a Website with Animated Aurora Background #css](https://www.youtube.com/watch?v=MxpDrULwejY)
  - 說明：
    1. SVG 專用 CSS 濾鏡效果 (filter: url(#goo) blur(40px)) ，比較 radial-gradient() 效能直接以的濾鏡效果 (filter: blur(40px)) 效能差異。
    2. JavaScript 監聽滑鼠移動事件，畫面上操作在讓圓形漸層跟隨座標操作。
